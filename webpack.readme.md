
# Webpack

Webpack is a tool mainly used for Module Bundling, which takes bunch of codes in a Single Page Application and converts them into a single optimized bundle, It can be customized by adding more loaders, plugins, configuring output, generating sourcemap etc....  

- #### Entry
    Entry is usually how we define an entry point to the application from where to where the code should be included in bundle, Entry can be defined as an object as well consisting of one ore more entry points which helps in code splitting.

- #### Loaders
    Loaders are used to pre-process the files maily based on file extension, for instance adding an loader will allow the file to be transformmed into an machine readbale code.

- #### Plugins
    Plugins are used to analyse, optimize and manage the entire build process, not just a file it works on a global level to perform optimizations to the bundle like code splitting, assets management etc...

    HtmlWebpackPlugin - Automatically generates Html file and injects bundled javascript code into it.

    BundleAnalyserPlugin  - Helps identifing analysing bundle size for the elements included.

    MiniCssExtractPlugin  - Helps seperating splitting all the css files to smaller chunks which allows loading the css files parelelly.

- #### Dev server
    Customizing the port and path when the application runs in development mode using webpack-dev-server.

- #### Output
    Customizing the name of build folder and generating source-map.
