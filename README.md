# Web components SEO
### Testing indexability of web components.

This website tests how standard and custom HTML tags are indexed by Google under different circumstances.


## Standard HTML

| Content          | Javascript | Link                                                                                    | Seen by Google |
|------------------|------------|-----------------------------------------------------------------------------------------|----------------|
| static html      | –          | [/html-static](https://marienfeldtom.github.io/web-components-seo/html-static)               | yes            |
| sync javascript  | ES5        | [/html-dynamic-sync](https://marienfeldtom.github.io/web-components-seo/html-dynamic-sync)   | yes            |
| async javascript | ES5        | [/html-dynamic-async](https://marienfeldtom.github.io/web-components-seo/html-dynamic-async) | yes            |


## Custom HTML

| Content          | Tag definition | Shadow DOM | Javascript | Link                                                                                                    | Seen by Google |
|------------------|----------------|------------|------------|---------------------------------------------------------------------------------------------------------|----------------|
| static html      | undefined      | —          | —          | [/undefined-static](https://marienfeldtom.github.io/web-components-seo/undefined-static)                     | yes            |
| static html      | immediate      | yes        | ES5        | [/shadow-static-sync-es5](https://marienfeldtom.github.io/web-components-seo/shadow-static-sync-es5)         | yes            |
| static html      | immediate      | yes        | ES6        | [/shadow-static-sync](https://marienfeldtom.github.io/web-components-seo/shadow-static-sync)                 | yes            |
| static html      | lazy           | yes        | ES6        | [/shadow-static-async](https://marienfeldtom.github.io/web-components-seo/shadow-static-async)               | yes            |
| sync javascript  | immediate      | no         | ES5        | [/noshadow-dynamic-sync-es5](https://marienfeldtom.github.io/web-components-seo/noshadow-dynamic-sync-es5)   | yes            |
| sync javascript  | immediate      | no         | ES6        | [/noshadow-dynamic-sync](https://marienfeldtom.github.io/web-components-seo/noshadow-dynamic-sync)           | yes            |
| sync javascript  | immediate      | yes        | ES5        | [/shadow-dynamic-sync-es5](https://marienfeldtom.github.io/web-components-seo/shadow-dynamic-sync-es5)       | yes            |
| sync javascript  | immediate      | yes        | ES6        | [/shadow-dynamic-sync](https://marienfeldtom.github.io/web-components-seo/shadow-dynamic-sync)               | yes            |
| async javascript | lazy           | no         | ES6        | [/noshadow-dynamic-async](https://marienfeldtom.github.io/web-components-seo/noshadow-dynamic-async)         | yes            |
| async javascript | lazy           | yes        | ES6        | [/shadow-dynamic-async](https://marienfeldtom.github.io/web-components-seo/shadow-dynamic-async)             | yes            |

### Conclusion

Google works great with web components (As of: 10/08/2024).