# Webpack 5 的一些主要特性和优化：

1、性能优化：
Webpack 5 在构建速度和性能方面进行了许多改进，包括更快的增量构建、更好的缓存和更低的内存使用。

2、Tree Shaking 改进：
Webpack 5 改进了 Tree Shaking 算法(嵌套的 tree-shaking、内部模块 tree-shaking、CommonJs Tree Shaking)，更好地消除未使用的代码，减小了生成的包的大小。

3、模块系统：
Webpack 5 引入了支持 ES 模块的新模块系统，这意味着它更好地与现代 JavaScript 生态系统兼容。

4、持久缓存：
Webpack 5 引入了持久性缓存，以便更容易地缓存构建结果，减少重复构建的需求。

5、代码分割(Code Splitting)改进：
Webpack 5 通过更智能的分割策略进一步改善了代码分割，以减少不必要的重复代码(entry、splitChunks、import)。

6、支持异步模块：
Webpack 5 允许在顶级模块中使用 await 关键字，这对于异步加载模块非常有用。
Webpack 5 能够处理 WebAssembly 模块，允许你在项目中使用 Wasm 文件。
异步的外部资源(async externals)。

7、模块联邦(Module Federation)：
Webpack 5 引入了模块联邦，允许不同的 Webpack 构建之间共享模块，从而实现更大规模的微前端架构。
