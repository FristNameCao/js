在 Vue 3 中，computed(()=>) 和 computed(()={}) 最主要的区别在于返回值类型和调用方式。

返回值类型
computed(()=>) 返回的是一个普通函数，是一个计算属性。当计算属性的依赖值发生改变时，会通知该属性来获取最新的计算结果。







computed(()={}) 返回的是一个对象 Property 方法，是一个缓存值，即 computed 的结果会被缓存起来，只有当依赖的变量改变时，才会重新计算并更新值。它还可以用于配置依赖项的 track，以便在调试时查看依赖项的变化情况。

调用方式
computed(()=>) 的使用方式与 Vue 2 中的计算属性相同，在模板中使用即可。

computed(()={}) 的使用方式与 Vue 2 中的 watch 非常相似，需要在深度监听时使用，例如：

Copy code
watchEffect(() => {
  const files = computed(() => {
    // 执行耗时操作
    console.log("3s事件")
    return getFilesMatchingSearchString(searchString.value);
  })
})
综上所述，两种使用方式各自适合不同的场景。如果您需要一个当依赖变化时获取最新值的计算属性，可以使用 computed(()=>)。如果您需要一个仅仅在依赖变化时重新计算值的缓存值，可以使用 computed(()={})。