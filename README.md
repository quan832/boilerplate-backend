@Quantran238

-   https://hocweb.vn/19-bi-mat-de-tro-thanh-dev-nodejs-xin-xo-2020-phan-1/
-   https://www.nearform.com/blog/managing-load-in-node-js-with-under-pressure/

# 1. SETUP PROJECT

1. Install base project

```bash
npm init
```

2. Add gitignore
3. Add jsconfig.json
4. Add eslint[https://blog.bitsrc.io/how-to-set-up-node-js-application-with-eslint-and-prettier-b1b7994db69f]

-   add eslint-plugin-unicorn[https://www.npmjs.com/package/eslint-plugin-unicorn]
-   add eslint-config-google[https://www.npmjs.com/package/eslint-config-google]
-   add eslint-config-prettier[https://www.npmjs.com/package/eslint-config-prettier]
-   add eslint-plugin-node[https://www.npmjs.com/package/eslint-plugin-node]

5. Add dotenv[https://www.npmjs.com/package/dotenv]

```bash
npm i dotenv
```

# 2. Initialize framework

1. Install fastify web server[https://www.fastify.io/docs/latest/Guides/Getting-Started/#your-first-server]

```bash
npm i fastify
```

-   make-promises-safe [https://github.com/mcollina/make-promises-safe]:A node.js module to make the use of promises safe.
-   fastify-plugins [https://github.com/fastify/fastify-plugin]: Fastify allows the user to extend its functionalities with plugins. A plugin can be a set of routes, a server decorator, or whatever. The API that you will need to use one or more plugins, is register.
-   fastify-autoload [https://github.com/fastify/fastify-autoload]: Convenience plugin for Fastify that loads all plugins found in a directory and automatically configures routes matching the folder structure.

2. Write code into app.js [https://www.youtube.com/watch?v=a9uEhq1uwNk]

-   ajv [https://ajv.js.org/guide/getting-started.html]: Ensure your data is valid as soon as it's received
-   ajv-complier [https://github.com/fastify/ajv-compiler]: The fastest JSON validator for Node.js and browser.
-   ajv-errors [https://www.npmjs.com/package/ajv-errors]: Custom error messages in JSON-Schema for Ajv validator
-   ajv-formats [https://www.npmjs.com/package/ajv-formats]: JSON Schema formats for Ajv
-   uuid eslint[https://www.npmjs.com/package/uuid]: To create a random UUID...
-   lodash [https://lodash.com/]
-   json-stringify-safe [https://www.npmjs.com/package/json-stringify-safe][https://developer.mozilla.org/en-us/docs/web/javascript/reference/errors/cyclic_object_value]: Like JSON.stringify, but doesn't throw on circular references.
-   pino [https://github.com/pinojs/pino/blob/master/docs/web.md#fastify]: Very low overhead Node.js logger.
-   pino-multi-stream [https://github.com/pinojs/pino-multi-stream]: Whereas pino allows only one destination stream, pino-multi-stream allows multiple destination streams via the same configuration API as Bunyan.
-   fastify-cors [https://github.com/fastify/fastify-cors]: fastify-cors enables the use of CORS in a Fastify application.
-   fastify-helmet [https://github.com/fastify/fastify-helmet][https://helmetjs.github.io/see-also/]: Important security headers for Fastify. It is a tiny wrapper around helmet.
-   fastify-formbody [https://github.com/fastify/fastify-formbody]: adds a content type parser for the content type application/x-www-form-urlencoded.
-   under-pressure [https://github.com/fastify/under-pressure]: Measure process load with automatic handling of "Service Unavailable" plugin for Fastify.
-   fastify-swagger [https://github.com/fastify/fastify-swagger]: A Fastify plugin for serving a Swagger UI, using Swagger (OpenAPI v2) or OpenAPI v3 schemas automatically generated from your route schemas, or from an existing Swagger/OpenAPI schema.
-   env-schema: Utility to check environment variables using JSON schema, Ajv, and dotenv.
-   link-module-alias[https://arunmichaeldsouza.com/blog/aliasing-module-paths-in-node-js]: There might be a possible solution to this "relative path hell" problem -
