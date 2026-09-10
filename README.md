# TEMARIO COMPLETO: DOMINAR ASP.NET (De Cero a Senior)

---

## MÓDULO 1: FUNDAMENTOS DE C# PARA ASP.NET

**Descripción:** Aprenderás los pilares del lenguaje C# que son indispensables antes de tocar cualquier proyecto ASP.NET. Sin estos fundamentos, el framework será incomprensible. Cubriremos desde la sintaxis básica hasta tipos genéricos, delegados y asincronía.

1. Historia y versiones de C# (.NET Framework, .NET Core, .NET 5/6/7/8)
2. Instalación del SDK de .NET
3. Entornos de desarrollo: Visual Studio, VS Code, Rider
4. Estructura de un programa C# (clase Program, método Main)
5. Instrucción `using` y namespaces
6. Tipos de datos primitivos: `int`, `float`, `double`, `decimal`, `bool`, `char`, `string`
7. Variables y constantes (`var`, `const`, `readonly`)
8. Inferencia de tipos con `var`
9. Nullable types (`int?`, `bool?`)
10. Operadores aritméticos (`+`, `-`, `*`, `/`, `%`)
11. Operadores de comparación (`==`, `!=`, `<`, `>`, `<=`, `>=`)
12. Operadores lógicos (`&&`, `||`, `!`)
13. Operador de coalescencia nula (`??`)
14. Operador condicional nulo (`?.`)
15. Operador ternario (`? :`)
16. Casting implícito y explícito
17. Conversión con `Convert` y `Parse` y `TryParse`
18. `if`, `else if`, `else`
19. `switch` y `switch` expression (C# 8+)
20. Ciclo `for`
21. Ciclo `while`
22. Ciclo `do-while`
23. `foreach` e interfaces `IEnumerable`
24. `break`, `continue`, `return`
25. Declaración de métodos (parámetros, tipo de retorno)
26. Parámetros por valor y por referencia (`ref`, `out`, `in`)
27. Parámetros opcionales y nombrados
28. Sobrecarga de métodos
29. Recursividad
30. Arreglos unidimensionales (`int[]`)
31. Arreglos multidimensionales (`int[,]`)
32. Arreglos jagged (`int[][]`)
33. `List<T>` y operaciones fundamentales
34. `Dictionary<TKey, TValue>`
35. `Queue<T>` y `Stack<T>`
36. `HashSet<T>`
37. `LinkedList<T>`
38. `SortedDictionary` y `SortedList`
39. `Tuple` y ValueTuple
40. Estructuras (`struct`)
41. Clases y objetos
42. Constructores y destructores
43. Campos y propiedades (auto-implemented, full property)
44. Propiedades init-only (C# 9)
45. Modificadores de acceso (`public`, `private`, `protected`, `internal`, `protected internal`)
46. Métodos estáticos y clases estáticas
47. Herencia y la palabra clave `base`
48. Polimorfismo (`virtual`, `override`, `abstract`)
49. Clases abstractas vs interfaces
50. Interfaces y múltiple implementación
51. Interfaces con implementación por defecto (C# 8)
52. `sealed` classes y métodos
53. `object` y métodos fundamentales (`ToString`, `Equals`, `GetHashCode`)
54. Boxing y unboxing
55. Tipos genéricos (`List<T>`, clases genéricas propias)
56. Restricciones genéricas (`where T : class`, `where T : new()`)
57. Métodos genéricos
58. Delegados (`Action`, `Func`, `Predicate`)
59. Expresiones lambda
60. Eventos y patrón publicador-suscriptor
61. Expresiones LINQ (sintaxis de consulta y de métodos)
62. LINQ: `Where`, `Select`, `OrderBy`, `GroupBy`
63. LINQ: `Any`, `All`, `First`, `FirstOrDefault`, `Count`, `Sum`
64. LINQ: `Join`, `GroupJoin`, `SelectMany`
65. Manejo de excepciones (`try`, `catch`, `finally`, `throw`)
66. Excepciones personalizadas
67. `Exception` filters (`when`)
68. Tipos por valor vs tipos por referencia
69. Paso de strings: inmutabilidad
70. `StringBuilder`
71. Expresiones regulares (`Regex`)
72. Manejo de fechas (`DateTime`, `DateOnly`, `TimeOnly`, `TimeSpan`)
73. Manejo de zonas horarias (`TimeZoneInfo`)
74. Manejo de cultura e invariantes (`CultureInfo`)
75. `enum` y flags
76. Atributos personalizados
77. Reflection básica (`GetType`, `typeof`, `Activator.CreateInstance`)
78. Serialización JSON con `System.Text.Json`
79. Serialización JSON con `Newtonsoft.Json`
80. Programación asíncrona: `async` y `await`
81. `Task` y `Task<T>`
82. `ValueTask<T>`
83. `CancellationToken` y cancelación cooperativa
84. `Parallel.ForEach` y `Task.WhenAll`/`WhenAny`
85. `SemaphoreSlim` y sincronización
86. Colecciones concurrentes (`ConcurrentDictionary`)
87. Pattern matching (`is`, `switch` patterns)
88. Records (C# 9)
89. Tuples patterns y positional patterns
90. Expressions-bodied members
91. Interpolación de strings (`$""`)
92. Raw string literals (C# 11)
93. File-scoped namespaces (C# 10)
94. Top-level statements
95. Global using directives
96. `Span<T>` y `Memory<T>` (conceptos)
97. Nullable reference types (C# 8+)
98. `required` members (C# 11)
99. Primary constructors (C# 12)
100. Collection expressions (C# 12)

---

## MÓDULO 2: INTRODUCCIÓN A .NET Y EL ECOSISTEMA

**Descripción:** Comprenderás la arquitectura del ecosistema .NET: cómo funciona el CLR, qué diferencia .NET Framework de .NET Core y .NET moderno, cómo se estructura un proyecto, qué es el SDK, el runtime, y cómo se compila y ejecuta tu código.

1. ¿Qué es .NET? Visión general del ecosistema
2. CLR (Common Language Runtime): rol y funcionamiento
3. JIT (Just-In-Time) compilation
4. IL (Intermediate Language) y metadatos
5. .NET Framework vs .NET Core vs .NET 5/6/7/8/9
6. .NET Standard y compatibilidad entre plataformas
7. LTS vs STS (soporte a largo plazo vs corto)
8. SDK de .NET: instalación y comandos `dotnet`
9. `dotnet new`, `dotnet build`, `dotnet run`
10. `dotnet add`, `dotnet remove`, `dotnet restore`
11. `dotnet test`, `dotnet publish`
12. Estructura de archivos de un proyecto .NET (`.csproj`, `.sln`)
13. El archivo `.csproj` y sus propiedades
14. `TargetFramework` y monikers (net8.0, net9.0)
15. `ImplicitUsings` y `Nullable`
16. NuGet: el gestor de paquetes
17. Instalación de paquetes NuGet desde CLI y Visual Studio
18. Creación de un paquete NuGet propio
19. Global tools y local tools
20. El archivo `global.json`
21. `Directory.Build.props` y `Directory.Build.targets`
22. Soluciones (`.sln`) y múltiples proyectos
23. Tipos de proyectos: consola, librería, web, worker
24. `dotnet watch` y hot reload
25. Garbage Collector (GC): generaciones 0, 1, 2
26. Finalizadores y `IDisposable`
27. Patrón `using` y `using` declaration
28. Ensamblados (assemblies): DLL y EXE
29. Strong naming
30. Global Assembly Cache (GAC) – legado
31. AOT (Ahead-of-Time) compilation en .NET 7+
32. Trimming y reducción de tamaño
33. Single-file publishing
34. Runtime identifiers (RID)
35. Plataformas soportadas (Windows, Linux, macOS)
36. Modelo de ejecución de aplicaciones ASP.NET Core
37. `WebApplication.CreateBuilder` vs `Host.CreateDefaultBuilder`
38. El patrón Generic Host
39. Kestrel: el servidor web integrado
40. Reverse proxy: IIS, Nginx, Apache
41. `appsettings.json` y jerarquía de configuración
42. Variables de entorno en .NET
43. User Secrets para desarrollo
44. Launch profiles (`launchSettings.json`)
45. Dependencias entre proyectos
46. Frameworks de referencia y transitive dependencies
47. Polyfills y compatibilidad hacia atrás
48. Source generators
49. Roslyn: el compilador de C#
50. Analyzers y Code Fixes
51. Interoperabilidad con código nativo (P/Invoke)
52. COM interop
53. Platform abstraction
54. `System.IO` y manejo de archivos
55. `System.Net.Http` y `HttpClient`
56. `System.Text.Json` vs `Newtonsoft.Json`
57. `System.Diagnostics` y `Activity` (tracing)
58. `System.Security.Cryptography`
59. TPL (Task Parallel Library)
60. Channels y productor-consumidor
61. Pipeline patterns
62. Memory pooling (`ArrayPool`, `ObjectPool`)
63. `Options Pattern` en .NET
64. `IConfiguration` e `IConfigurationRoot`
65. `IHostedService` y ciclo de vida del host
66. `BackgroundService`
67. `IHostApplicationLifetime` y graceful shutdown
68. Health checks en .NET
69. Metrics y `System.Diagnostics.Metrics`
70. OpenTelemetry en .NET
71. Distributed tracing con `Activity`
72. Logging: `ILogger<T>` y providers
73. Serilog como alternativa
74. NLog como alternativa
75. Manejo de culturas y localización
76. Resolución de dependencias manual vs DI container
77. `IServiceProvider` y `IServiceCollection`
78. Ciclo de vida de servicios (Transient, Scoped, Singleton)
79. `HttpClientFactory`
80. `IHttpClientFactory` y polly para resiliencia
81. Rate limiting con `System.Threading.RateLimiting`
82. `TimeProvider` abstraction (.NET 8)
83. `Keyed Services` (.NET 8)
84. Native AOT support (.NET 8)
85. Interceptores de compilación
86. Experimental attributes (.NET 8)
87. .NET Aspire (orquestación de apps distribuidas)
88. Hot reload en detalle
89. Diagnostics y `EventSource`
90. Performance counters
91. `BenchmarkDotNet` para microbenchmarks
92. Comparación con otros ecosistemas (Java/Spring, Node.js/Express)
93. Comunidad y recursos oficiales (docs.microsoft.com / learn.microsoft.com)
94. Roadmap de versiones de .NET
95. Licencias y open source
96. Long-term support y ciclo de vida
97. Portabilidad de código entre versiones
98. Migration paths (de .NET Framework a .NET 8)
99. Upgrade Assistant tool
100. Buenas prácticas generales del ecosistema

---

## MÓDULO 3: FUNDAMENTOS DE HTML, CSS Y JAVASCRIPT PARA DESARROLLADORES BACKEND

**Descripción:** Aunque tu enfoque sea backend, necesitas entender las tecnologías del lado del cliente para construir aplicaciones web completas con ASP.NET. Aprenderás lo esencial de HTML, CSS y JavaScript que todo desarrollador ASP.NET debe conocer.

1. ¿Qué es HTTP? Métodos (GET, POST, PUT, DELETE, PATCH)
2. Ciclo request-response
3. Headers HTTP comunes (Content-Type, Authorization, Cache-Control)
4. Códigos de estado HTTP (200, 301, 302, 400, 401, 403, 404, 500)
5. Cookies y sesiones desde la perspectiva HTTP
6. HTTPS y certificados TLS
7. Estructura básica de un documento HTML
8. Etiquetas semánticas (`<header>`, `<nav>`, `<main>`, `<section>`, `<footer>`)
9. Formularios HTML (`<form>`, `<input>`, `<select>`, `<textarea>`)
10. Atributos de formulario (`action`, `method`, `enctype`)
11. Validación nativa de formularios HTML5
12. Tablas HTML
13. Enlaces y navegación (`<a>`)
14. Imágenes y multimedia
15. Meta tags y SEO básico
16. Introducción a CSS: selectores y propiedades
17. Modelo de caja (box model): margin, padding, border
18. Display: block, inline, inline-block, flex, grid
19. Flexbox: conceptos básicos
20. CSS Grid: conceptos básicos
21. Posicionamiento (relative, absolute, fixed, sticky)
22. Responsive design y media queries
23. Unidades relativas (rem, em, vh, vw, %)
24. Variables CSS (custom properties)
25. Transiciones y animaciones CSS básicas
26. Bootstrap: sistema de grillas
27. Bootstrap: componentes comunes (navbar, cards, modals, alerts)
28. Bootstrap: formularios y validación
29. Introducción a JavaScript: variables y tipos
30. Funciones en JavaScript
31. DOM (Document Object Model)
32. Selección de elementos (`getElementById`, `querySelector`)
33. Manipulación del DOM (crear, modificar, eliminar elementos)
34. Eventos del DOM (click, submit, change, keydown)
35. Event delegation
36. `addEventListener` y `removeEventListener`
37. JavaScript asíncrono: callbacks
38. Promises en JavaScript
39. `async/await` en JavaScript
40. `fetch` API para llamadas HTTP
41. JSON en JavaScript (`JSON.parse`, `JSON.stringify`)
42. Manipulación de formularios con JavaScript
43. Validación del lado del cliente
44. Arrow functions
45. Destructuring assignment
46. Spread operator
47. Template literals
48. Módulos ES6 (`import/export`)
49. `let` vs `const` vs `var`
50. Closures
51. Scope y hoisting
52. `this` en JavaScript
53. Prototypes y herencia
54. Clases en JavaScript (ES6)
55. `Map`, `Set`, `WeakMap`
56. Iteradores y generators
57. `Proxy` y `Reflect`
58. Manejo de errores (`try/catch` en JS)
59. `localStorage` y `sessionStorage`
60. `cookie` en JavaScript
61. AJAX: concepto e historia
62. XMLHttpRequest vs Fetch
63. Consumo de una API REST desde JavaScript
64. Envío de formularios con Fetch
65. Interceptor pattern con Fetch
66. Manejo de CORS desde el cliente
67. jQuery: selección y manipulación (conocimiento básico)
68. jQuery: AJAX con `$.ajax`, `$.get`, `$.post`
69. TypeScript: tipos básicos
70. TypeScript: interfaces y tipos
71. TypeScript: clases y herencia
72. TypeScript: genéricos
73. TypeScript: módulos
74. TypeScript: configuración (`tsconfig.json`)
75. Libman: gestor de librerías del lado del cliente en ASP.NET
76. Bundling y minificación en ASP.NET
77. Webpack: conceptos básicos
78. Librerías útiles: Axios, Lodash, Day.js
79. Npm y Node.js: por qué los necesita un desarrollador ASP.NET
80. `package.json` y gestión de dependencias
81. `wwwroot`: la carpeta de archivos estáticos
82. Static files middleware en ASP.NET Core
83. CDN y uso de librerías desde CDN
84. Favicons y assets
85. Accesibilidad web básica (ARIA, contraste, keyboard navigation)
86. Lighthouse y auditorías de rendimiento
87. DevTools del navegador: Network tab
88. DevTools: Console y debugging
89. DevTools: Elements y CSS
90. DevTools: Performance y Memory
91. Preprocesadores CSS: Sass/SCSS (concepto)
92. Tailwind CSS (concepto y cuándo usarlo)
93. Iconos: Font Awesome, Bootstrap Icons
94. Fuentes web: Google Fonts
95. Imágenes responsivas (`srcset`, `<picture>`)
96. Lazy loading de imágenes
97. Service Workers (concepto básico)
98. Progressive Web Apps (PWA) (concepto)
99. Single Page Application (SPA) vs Multi-Page Application (MPA)
100. Cómo Razor, Blazor y JavaScript se integran en ASP.NET

---

## MÓDULO 4: PATRÓN MVC – CONCEPTOS TEÓRICOS

**Descripción:** Antes de implementar, necesitas entender profunda y teóricamente el patrón Model-View-Controller. Aprenderás por qué existe, qué problemas resuelve, cómo se relaciona con otros patrones, y las convenciones que gobiernan su uso en ASP.NET Core MVC.

1. ¿Qué es un patrón de diseño de software?
2. Historia del patrón MVC (Trygve Reenskaug, 1979)
3. Separación de responsabilidades (SoC)
4. Los tres componentes: Model, View, Controller
5. Flujo de una solicitud en MVC
6. El Model: qué contiene y qué no
7. Domain Models vs View Models vs DTOs
8. El View: responsabilidades del renderizado
9. El Controller: orquestador del flujo
10. Diferencia entre MVC, MVP y MVVM
11. MVC web vs MVC desktop
12. Front Controller pattern
13. Page Controller pattern
14. MVC en ASP.NET Core vs ASP.NET MVC 5 (Framework)
15. Convención sobre configuración (conventions over configuration)
16. Estructura de carpetas estándar (Controllers, Views, Models, wwwroot)
17. Naming conventions en MVC
18. Ciclo de vida de una solicitud en ASP.NET Core MVC
19. Action methods
20. ActionResult y tipos de retorno
21. ViewResult, JsonResult, RedirectResult, FileResult
22. ViewData, ViewBag y TempData
23. Strongly-typed views
24. Model binding: concepto
25. Model validation: concepto
26. Routing: URL patterns y segments
27. Convention-based routing vs Attribute-based routing
28. Route parameters y query strings
29. Areas: organización de proyectos grandes
30. Partial views: reutilización de UI
31. Layouts: plantillas maestras
32. Sections y RenderSection
33. `_ViewImports.cshtml` y `_ViewStart.cshtml`
34. Tag Helpers en ASP.NET Core
35. HTML Helpers (legado)
36. Razor syntax: código embebido en vistas
37. Scaffolding: generación automática de código
38. CRUD operations en MVC
39. PRG pattern (Post-Redirect-Get)
40. Anti-forgery tokens (CSRF protection)
41. Dependency Injection en Controllers
42. Filters: Authorization, Action, Result, Exception, Resource
43. Filtro personalizado
44. Global filters
45. Action filters vs Result filters
46. Exception filters vs Middleware de errores
47. Areas avanzadas: routing con areas
48. Custom model binder
49. Custom model validator
50. Remote validation
51. Display templates y Editor templates
52. `Html.DisplayFor` y `Html.EditorFor`
53. Custom HTML Helpers
54. Custom Tag Helpers
55. `asp-for`, `asp-action`, `asp-controller` Tag Helpers
56. Form Tag Helper
57. Input Tag Helper
58. Select Tag Helper
59. Anchor Tag Helper
60. Environment Tag Helper
61. Cache Tag Helper
62. Image Tag Helper (CDN fallback)
63. Link Tag Helper
64. Script Tag Helper
65. Validation Tag Helpers (`asp-validation-for`, `asp-validation-summary`)
66. Globalization y localización en MVC
67. `IStringLocalizer` y `IViewLocalizer`
68. Data annotations de localización
69. Cultura por URL, cookie o header
70. Error handling global con `IExceptionFilter`
71. Error pages personalizadas (404, 500)
72. Logging en controllers y acciones
73. Filtros de autorización personalizados
74. Claims-based authorization
75. Policy-based authorization
76. `[AllowAnonymous]` y `[Authorize]`
77. Dependency Injection en filtros
78. Service filter vs Type filter
79. `IActionContextAccessor`
80. `IUrlHelper` y generación de URLs
81. `TempData` con proveedores (Session vs Cookie)
82. Complex model binding (nested objects, collections)
83. FromQuery, FromRoute, FromBody, FromForm attributes
84. File uploads con `IFormFile`
85. Multiple file uploads
86. File download con `FileContentResult`
87. JSON responses personalizadas
88. Content negotiation en MVC
89. Async actions
90. Unit testing de controllers
91. Integration testing de MVC
92. Performance considerations en vistas
93. View compilation vs runtime compilation
94. Precompiled views
95. MVC vs Razor Pages: cuándo usar cada uno
96. MVC + API en el mismo proyecto
97. Estructura de proyectos para aplicaciones grandes
98. Feature folders vs architecture por capas
99. Prácticas de mantenibilidad en MVC
100. Patrones de diseño comunes en aplicaciones MVC (Repository, Service Layer)

---

## MÓDULO 5: ASP.NET CORE MVC – PRIMEROS PASOS PRÁCTICOS

**Descripción:** Crearás tu primera aplicación ASP.NET Core MVC desde cero. Aprenderás a crear el proyecto, entender la estructura generada, ejecutar la app, crear controllers, views y models, y realizar operaciones CRUD básicas.

1. Crear proyecto con `dotnet new mvc`
2. Explorar la estructura de carpetas generada
3. El archivo `Program.cs` y la configuración del builder
4. `app.MapControllerRoute` y convenciones de ruta
5. `wwwroot`: archivos estáticos (CSS, JS, imágenes)
6. `Controllers/HomeController.cs`
7. `Views/Home/Index.cshtml`
8. `Views/Shared/_Layout.cshtml`
9. `Views/Shared/_ValidationScriptsPartial.cshtml`
10. `Views/_ViewImports.cshtml`
11. `Views/_ViewStart.cshtml`
12. `Models/ErrorViewModel.cs`
13. Ejecutar la app con `dotnet run`
14. Explorar la app en el navegador
15. Hot reload y watch mode (`dotnet watch`)
16. Crear un Controller desde cero
17. Crear una View desde cero
18. Crear un Model desde cero
19. Pasar datos del Controller a la View con un Modelo
20. Usar ViewData y ViewBag (para entenderlos, no para producción)
21. Crear un modelo simple (ej. `Producto`)
22. Crear un controller CRUD para Producto
23. Crear la vista Index (lista)
24. Crear la vista Create (formulario)
25. Crear la vista Details
26. Crear la vista Edit
27. Crear la vista Delete (confirmación)
28. Validación del lado del servidor con Data Annotations
29. `[Required]`, `[StringLength]`, `[Range]`, `[EmailAddress]`
30. Mostrar errores de validación en la vista
31. Validación del lado del cliente con jQuery Validation
32. Usar scaffolding para generar CRUD automáticamente
33. Customizar el código generado por scaffolding
34. Implementar una lista en memoria (sin base de datos aún)
35. `List<T>` como almacenamiento temporal
36. Búsqueda y filtrado simple
37. Paginación manual
38. Ordenamiento de columnas
39. Mensajes de éxito con TempData
40. Implementar la página de Error
41. Personalizar la página de Error 404
42. Cambiar el Layout (colores, logo, navegación)
43. Agregar una nueva sección al Layout
44. Crear una Partial View
45. Usar `Html.Partial` y `<partial>` Tag Helper
46. Crear un componente de resumen (widget reutilizable)
47. Configurar un nuevo route pattern
48. Usar attribute routing en el controller
49. Parámetros de ruta opcionales
50. Restricciones de ruta (`int`, `guid`, `regex`)
51. Usar `[HttpGet]` y `[HttpPost]`
52. Usar `[HttpPut]` y `[HttpDelete]`
53. `RedirectToAction` y redirecciones
54. `return View()` vs `return RedirectToAction()`
55. `return PartialView()`
56. `return Json()`
57. `return File()` para descargas
58. `return NotFound()`, `return BadRequest()`
59. Inyección de dependencias en un Controller
60. Crear un servicio simple (ej. `IProductoService`)
61. Registrar el servicio en `Program.cs`
62. Inyectar y usar el servicio en el Controller
63. Configurar appsettings.json con datos propios
64. Leer configuración con `IConfiguration`
65. Usar el Options Pattern (`IOptions<T>`)
66. Configurar logging en `Program.cs`
67. Agregar logs en el Controller con `ILogger<T>`
68. Agregar un middleware personalizado
69. Middleware de tiempo de ejecución de solicitud
70. Usar `app.UseExceptionHandler`
71. Usar `app.UseStatusCodePages`
72. Habilitar archivos estáticos (`app.UseStaticFiles`)
73. Agregar Bootstrap al proyecto
74. Crear una vista responsive con Bootstrap
75. Usar Tag Helpers en formularios
76. Crear un modelo con relación (ej. `Categoria` y `Producto`)
77. SelectList y dropdown en formularios
78. Checkbox y radio buttons en formularios
79. Formularios con múltiples campos
80. File upload en un formulario
81. Preview de imagen subida
82. Exportar datos a CSV desde un Controller
83. Crear una API controller básico (retorna JSON)
84. Consumir la API desde la misma app con JavaScript
85. Usar `HttpClient` para consumir una API externa
86. Mostrar datos de API externa en una vista
87. Implementar un buscador simple
88. Autocomplete con JavaScript y una API
89. Alertas con `TempData`
90. Confirmación de eliminación con modal Bootstrap
91. Proteger un formulario con Anti-Forgery Token
92. Crear un filtro de acción personalizado (log de tiempos)
93. Crear un filtro de excepción personalizado
94. Organizar controllers en Areas
95. Crear un Area completa
96. Navegación entre Areas
97. Publicar la app con `dotnet publish`
98. Publicar como self-contained
99. Publicar como framework-dependent
100. Ejecutar el binario publicado y verificar funcionamiento

---

## MÓDULO 6: ROUTING Y NAVEGACIÓN EN ASP.NET CORE

**Descripción:** Dominarás el sistema de routing de ASP.NET Core, que determina cómo las URLs del navegador se mapean a los controllers y acciones. Aprenderás routing convencional, por atributos, parámetros, restricciones, y cómo funciona internamente el middleware de endpoint routing.

1. ¿Qué es Routing y por qué es importante?
2. Endpoint Routing en ASP.NET Core (introducido en 2.2)
3. `app.MapControllerRoute` y routing convencional
4. Convenciones de ruta por defecto: `{controller=Home}/{action=Index}/{id?}`
5. Valores por defecto en rutas
6. Routing por atributos (`[Route]`)
7. `[Route("api/[controller]")]` y tokens de ruta
8. `[HttpGet]`, `[HttpPost]`, `[HttpPut]`, `[HttpDelete]`, `[HttpPatch]`
9. Combinar rutas de controller con rutas de acción
10. Rutas absolutas vs relativas en atributos
11. Parámetros de ruta (`{id}`, `{slug}`)
12. Parámetros opcionales (`{id?}`)
13. Parámetros con valores por defecto (`{page=1}`)
14. Restricciones de tipo (`{id:int}`, `{price:decimal}`)
15. Restricciones de rango (`{id:int:min(1)}`, `{year:int:range(2000,2030)}`)
16. Restricciones de longitud (`{name:minlength(3):maxlength(50)}`)
17. Restricción regex (`{slug:regex(^[a-z0-9-]+$)}`)
18. Restricciones personalizadas (`IRouteConstraint`)
19. Query strings: cómo se leen
20. `[FromQuery]` attribute
21. Binding de múltiples parámetros desde query string
22. Clases como modelo de query string
23. Route order y precedencia
24. Ambiguous route resolution
25. Link generation con `IUrlHelper`
26. `Url.Action()`, `Url.RouteUrl()`
27. Tag Helpers y generación de links (`asp-action`, `asp-controller`, `asp-route-*`)
28. Routing con Areas
29. `[Area("Admin")]` attribute
30. Rutas de fallback (`MapFallbackToFile`, `MapFallbackToController`)
31. Endpoint routing middleware (`app.UseRouting()`, `app.UseEndpoints()`)
32. `app.MapGet`, `app.MapPost` (Minimal APIs)
33. `app.MapControllers()`, `app.MapRazorPages()`
34. Endpoint metadata
35. `IEndpointRouteProvider`
36. Endpoint filters (Minimal APIs)
37. Routing y middleware pipeline: orden de ejecución
38. Diferencia entre `app.UseRouting()` y `app.UseEndpoints()`
39. Data Tokens en rutas
40. Custom route constraint paso a paso
41. Rutas con parámetros catch-all (`{*slug}`)
42. Lowercase URLs
43. Trailing slashes
44. URL rewriting middleware
45. `app.UseRewriter()` y reglas de rewrite
46. Redirecciones 301 vs 302 en routing
47. Routing en aplicaciones SPA (Single Page Application)
48. `MapFallbackToFile("index.html")` para SPA
49. Routing y versionado de APIs (concepto)
50. Convention-based routing para múltiples controllers
51. Attribute routing para múltiples controllers
52. Combinar ambos tipos de routing en un proyecto
53. Routing y middleware de autorización por endpoint
54. `[Authorize]` en endpoints específicos
55. Routing y CORS policies por endpoint
56. Routing y output caching por endpoint
57. Routing y rate limiting por endpoint
58. Routing y health checks endpoints
59. Routing y minimal API groups (`MapGroup`)
60. Nested route groups
61. OpenAPI metadata en routing
62. Routing y `IActionDescriptorCollectionProvider`
63. Debugging de rutas (no match, ambiguous match)
64. Logging de routing
65. Routing y culture (localización de URLs)
66. Routing y SEO (URL amigables)
67. Slug-based routing (blog posts con slug)
68. Hierarchical routing (ej. `/productos/categoria/subcategoria/producto`)
69. Versioned URLs (`/v1/productos`, `/v2/productos`)
70. Routing y HTTP methods no estándar
71. Content negotiation en relación con routing
72. Routing y CORS preflight requests
73. Routing y middleware de response caching
74. Routing y middleware de request decompression
75. Endpoint metadata personalizada
76. `IEndpointConventionBuilder`
77. `WithName()`, `WithTags()`, `WithOpenApi()`
78. `RequireAuthorization()` en grupos
79. `RequireCors()` en grupos
80. `RequireRateLimiting()` en grupos
81. `AddEndpointFilter` en Minimal APIs
82. Routing y testing (testeo de rutas)
83. Integration tests con `WebApplicationFactory`
84. Testear que una ruta retorna el código correcto
85. Testear route parameters binding
86. Routing y anti-forgery tokens
87. Routing y response caching por ruta
88. Routing y output caching por ruta
89. Rutas dinámicas (runtime configurable)
90. Routing y API Gateway patterns
91. Reverse proxy routing (YARP)
92. YARP: configuración básica
93. YARP: transformaciones de ruta
94. YARP: load balancing
95. Routing y microservicios
96. API Gateway routing patterns
97. Routing y health check paths configurables
98. Routing y Swagger UI path configurables
99. Routing y middleware de path base (`UsePathBase`)
100. Best practices de diseño de URLs en ASP.NET

---

## MÓDULO 7: RAZOR VIEW ENGINE

**Descripción:** Dominarás Razor, el motor de plantillas de ASP.NET Core. Aprenderás su sintaxis, cómo embeber código C# en HTML, expresiones, control de flujo, layouts, partial views, sections, Tag Helpers, y todas las herramientas que Razor ofrece para construir interfaces web dinámicas.

1. ¿Qué es Razor? Historia y evolución
2. Sintaxis básica: `@` para código C#
3. `@model` directive
4. `@using` directive
5. `@inject` directive (inyección de servicios en vistas)
6. `@functions` block
7. `@{ }` code blocks
8. Expresiones Razor: `@Model.Nombre`
9. Expresiones HTML-encoded vs raw (`@Html.Raw()`)
10. `@if`, `@else if`, `@else`
11. `@switch`
12. `@for` loop
13. `@foreach` loop
14. `@while` y `@do-while`
15. `@try`, `@catch`, `@finally`
16. `@lock`
17. Transición HTML-to-code con `<text>` tag
18. `@:` para transición de línea
19. Implicit expressions
20. Explicit expressions: `@(expression)`
21. Combining HTML y código C#
22. Razor comments (`@* *@`)
23. `_ViewImports.cshtml`: `@using`, `@addTagHelper`, `@model`
24. `_ViewStart.cshtml`: layout configuration
25. `@RenderBody()`
26. `@RenderSection("name", required: false)`
27. `@section name { }` en vistas
28. `@RenderSectionAsync("name")`
29. Nested layouts
30. Partial Views: creación y uso
31. `<partial name="_MyPartial" model="data" />`
32. `@await Html.PartialAsync("_MyPartial", model)`
33. `_ViewImports` y Tag Helper imports
34. Tag Helpers vs HTML Helpers
35. `AnchorTagHelper` (`asp-action`, `asp-controller`)
36. `FormTagHelper` (`asp-action`, `asp-controller`, `asp-antiforgery`)
37. `InputTagHelper` (`asp-for`)
38. `LabelTagHelper` (`asp-for`)
39. `SelectTagHelper` (`asp-for`, `asp-items`)
40. `TextAreaTagHelper` (`asp-for`)
41. `ValidationMessageTagHelper` (`asp-validation-for`)
42. `ValidationSummaryTagHelper` (`asp-validation-summary`)
43. `ImageTagHelper` (`asp-append-version`)
44. `LinkTagHelper` (`asp-href-include`, `asp-href-exclude`)
45. `ScriptTagHelper` (`asp-src-include`, `asp-append-version`)
46. `EnvironmentTagHelper` (`include`, `exclude`)
47. `CacheTagHelper` (`expires-after`, `expires-on`, `vary-by-*`)
48. `DistributedCacheTagHelper`
49. Crear Tag Helpers personalizados (`ITagHelper`)
50. `TagHelper`, `TagHelper<T>`, `ITagHelperProcessAsync`
51. `TagHelperContext` y `TagHelperOutput`
52. `HtmlTargetElement` attribute
53. `HtmlAttributeNotBound` attribute
54. `ViewContext` attribute
55. Passthrough attributes en Tag Helpers
56. Tag Helpers child content
57. HTML Helpers (legado): `Html.TextBoxFor`, `Html.DropDownListFor`
58. `Html.EditorFor` y display/editor templates
59. `Html.DisplayFor` y display templates
60. `@Html.Partial` vs `<partial>` Tag Helper
61. `@Html.BeginForm` vs `<form>` Tag Helper
62. View Components: concepto
63. Crear un View Component
64. `IViewComponentResult`
65. `InvokeAsync` y `Invoke`
66. Invocar View Components: `@await Component.InvokeAsync("Name")`
67. `<vc:name />` Tag Helper para View Components
68. View Component parameters
69. Default view naming conventions para View Components
70. View Components vs Partial Views vs Child Actions
71. ViewData y ViewBag: diferencias y uso
72. TempData: concepto y proveedores
73. TempData con `ITempDataProvider`
74. ViewData attribute
75. ViewData y ViewBag en Layouts
76. Strongly-typed views con `@model`
77. Model expression en Tag Helpers
78. `@model` con tipos anónimos (no recomendado)
79. `@model` con genéricos (List, IEnumerable)
80. Model metadata y `ModelExplorer`
81. `Html.DisplayNameFor`, `Html.DisplayTextFor`
82. Display attributes y `DisplayFormat`
83. `UIHint` attribute
84. Scaffold templates
85. Custom scaffolding templates
86. Razor class libraries
87. Razor compilación en tiempo de desarrollo vs producción
88. `RazorRuntimeCompilation` NuGet package
89. Precompiled Razor views
90. Razor y namespaces globales
91. Razor directives: `@attribute`, `@implements`
92. Razor y code-behind (no direct, pero pattern alternativo)
93. Tag Helper testing
94. View Component testing
95. Razor pages vs Razor views (diferencia)
96. Razor syntax performance considerations
97. XSS prevention y encoding en Razor
98. Razor y JavaScript interop
99. Debugging Razor views
100. Best practices de organización de vistas

---

## MÓDULO 8: MODEL BINDING Y VALIDACIÓN

**Descripción:** Entenderás cómo ASP.NET Core convierte los datos entrantes de requests HTTP (formularios, query strings, rutas, JSON) en objetos C# que tus controllers pueden usar. También dominarás el sistema de validación que garantiza que los datos sean correctos antes de procesarlos.

1. ¿Qué es Model Binding?
2. Fuentes de datos: query string, route data, form data, headers, body
3. Orden de búsqueda de fuentes (IValueProvider)
4. Binding de tipos simples (string, int, DateTime)
5. Binding de tipos complejos (objetos con propiedades)
6. Binding de listas (`List<T>`, `IEnumerable<T>`)
7. Binding de diccionarios (`Dictionary<string, string>`)
8. Binding de objetos anidados (propiedades dentro de propiedades)
9. Binding de archivos (`IFormFile`, `IFormFileCollection`)
10. `[FromQuery]` attribute
11. `[FromRoute]` attribute
12. `[FromForm]` attribute
13. `[FromBody]` attribute
14. `[FromHeader]` attribute
15. `[FromServices]` attribute
16. Prefix y naming conventions para binding
17. `Name` property en attributes (`[FromQuery(Name = "q")]`)
18. Custom model binder: `IModelBinder`
19. `IModelBinderProvider`
20. Registering custom model binders
21. Model binding con `BinderType`
22. BindNever attribute
23. BindRequired attribute
24. ComplexTypeModelBinder
25. `BodyModelBinder` y JSON deserialization
26. `FormFileModelBinder`
27. `SimpleTypeModelBinder`
28. `CollectionModelBinder`
29. `DictionaryModelBinder`
30. `ArrayModelBinder`
31. Model binding con tipos nullable
32. Model binding con enums
33. Model binding con DateTime y formatos
34. Model binding con GUID
35. Model binding con IFormFile y múltiples archivos
36. Model binding y cultura (globalización)
37. Prefix en formularios y binding
38. `ModelState.IsValid` y validación
39. `ModelState` dictionary y errores
40. Data Annotations para validación
41. `[Required]` y configuración de AllowEmptyStrings
42. `[StringLength]` (mínimo y máximo)
43. `[MinLength]` y `[MaxLength]`
44. `[Range]` para numéricos
45. `[RegularExpression]`
46. `[EmailAddress]`
47. `[Phone]`
48. `[Url]`
49. `[CreditCard]`
50. `[Compare]` (comparar dos propiedades)
51. `[DataType]` attribute
52. `[Display]` y `[DisplayName]`
53. `[DisplayFormat]`
54. `[Editable]`
55. `[HiddenInput]`
56. `[ScaffoldColumn]`
57. `ValidationAttribute` base class
58. Custom validation attribute (ej. `NoSpacesAttribute`)
59. `IValidatableObject` interface
60. Validation con múltiples propiedades (cross-property validation)
61. `ValidationContext`
62. Server-side validation workflow
63. Client-side validation con jQuery Validation
64. `jquery.validate.js` y `jquery.validate.unobtrusive.js`
65. `data-val`, `data-val-required` attributes generados por Tag Helpers
66. Remote validation: `[Remote]` attribute
67. Remote validation: implementar el endpoint
68. Custom client-side validation adapter
69. Validation con FluentValidation
70. FluentValidation: crear un validador
71. FluentValidation: reglas comunes
72. FluentValidation: validación condicional
73. FluentValidation: custom validators
74. FluentValidation: integración con ASP.NET Core
75. FluentValidation: mensajes de error personalizados
76. Validation y API Controllers
77. `ApiController` attribute y validación automática
78. InvalidModelStateResponseFactory
79. ProblemDetails para errores de validación en API
80. Validation summary vs field-level errors en vistas
81. `asp-validation-summary="All"` vs `"ModelOnly"` vs `"None"`
82. `asp-validation-for` y errores por campo
83. Estilizar errores de validación con CSS
84. Validation y globalization (mensajes localizados)
85. `ValidationAttribute.ErrorMessageResourceType`
86. `[Required(ErrorMessage = "...")]`
87. `IStringLocalizer` en validación
88. Validación en Blazor forms
89. `EditContext` y `ValidationMessageStore`
90. `DataAnnotationsValidator` component en Blazor
91. Validación en Minimal APIs con filters
92. `AddFluentValidationAutoValidation`
93. `AddFluentValidationClientsideAdapters`
94. Model binding performance considerations
95. `DisableFormValueModelBindingAttribute`
96. Multipart form data y streaming
97. Large file uploads sin model binding
98. Model binding y security (over-posting / mass assignment)
99. `[Bind]` attribute para evitar over-posting
100. DTOs vs usar directamente entidades: best practices

---

## MÓDULO 9: FORMULARIOS Y DATOS EN ASP.NET CORE MVC

**Descripción:** Aprenderás a construir formularios completos en ASP.NET Core MVC: desde formularios simples hasta formularios complejos con múltiples colecciones, archivos, campos dinámicos, y cómo manejar la persistencia de datos a través de formularios.

1. Crear un formulario HTML con Tag Helper `<form>`
2. `asp-action` y `asp-controller` en formularios
3. `asp-antiforgery` y tokens CSRF
4. GET vs POST en formularios
5. Campos de texto: `<input asp-for="Nombre" />`
6. Campos de contraseña: `type="password"`
7. Campos numéricos: `type="number"`
8. Campos de fecha: `type="date"`
9. Campos ocultos: `<input type="hidden" asp-for="Id" />`
10. Textareas: `<textarea asp-for="Descripcion"></textarea>`
11. Dropdowns: `<select asp-for="CategoriaId" asp-items="Model.Categorias"></select>`
12. `SelectListItem` y ` SelectList`
13. Dropdown con opción por defecto ("-- Seleccione --")
14. Multi-select: `<select multiple>`
15. Checkboxes: `<input type="checkbox" asp-for="Activo" />`
16. Lista de checkboxes (binding a `List<int>`)
17. Radio buttons: `<input type="radio" asp-for="Genero" value="M" />`
18. File upload: `<input type="file" asp-for="Foto" />`
19. `IFormFile` en el modelo
20. Validación del tipo de archivo
21. Validación del tamaño del archivo
22. Guardar archivo en disco
23. Guardar archivo en base de datos (como bytes)
24. Guardar archivo en Azure Blob Storage
25. Múltiples archivos: `IFormFileCollection`
26. Preview de imagen antes de subir (JavaScript)
27. Drag & drop file upload
28. Formulario con modelo complejo (objeto con propiedades anidadas)
29. Formulario con lista dinámica de elementos (add/remove)
30. Editor template para item de lista
31. Formularios con colecciones: binding de listas de inputs
32. Naming convention para listas: `[0].Property`, `[1].Property`
33. `EditorFor` con colecciones
34. Formulario maestro-detalle (ej. Pedido con líneas)
35. Campos readonly y disabled
36. Campos con formato: `DisplayFormat`
37. Campos calculados (no enviados al servidor)
38. Multi-step formularios (wizard)
39. TempData para persistir datos entre steps
40. Session para persistir estado del wizard
41. Formulario de búsqueda con filtros múltiples
42. Formulario de reporte con parámetros
43. Date range picker
44. Cascading dropdowns (cambiar opciones según selección)
45. AJAX form submission (sin recargar página)
46. `$.ajax` POST con FormData
47. `fetch` API con FormData
48. Return `PartialView` desde AJAX
49. Return `Json` desde AJAX
50. Unobtrusive AJAX (`asp-ajax="true"`)
51. Form submission y PRG pattern
52. Anti-forgery token y AJAX
53. `@Html.AntiForgeryToken()` con AJAX headers
54. Formulario con campos condicionales (mostrar/ocultar)
55. Formulario con validación remota
56. Formulario de login
57. Formulario de registro
58. Formulario de perfil de usuario
59. Formulario de cambio de contraseña
60. Formulario de contacto
61. Formulario de upload masivo (CSV import)
62. Parsing de CSV en el controller
63. Formulario de exportación (seleccionar formato)
64. Exportar a Excel (CSV)
65. Exportar a PDF con librería (Rotativa, DinkToPdf)
66. Formulario con rich text editor (TinyMCE, CKEditor)
67. Formulario con autocomplete
68. Formulario con Google reCAPTCHA
69. Honeypot fields para anti-spam
70. Rate limiting en formularios
71. Confirmación antes de enviar (JavaScript confirm)
72. Success/error messages post-submit
73. Form styling con Bootstrap
74. Form floating labels (Bootstrap 5)
75. Input groups (Bootstrap)
76. Custom select styling
77. Form horizontal layout vs vertical
78. Responsive forms
79. Form accessibility (labels, aria attributes)
80. Form keyboard navigation
81. Form autosave (debounced AJAX)
82. Form dirty tracking (warn on unsaved changes)
83. Server-side form processing pipeline
84. Idempotent form submission (token-based)
85. Duplicate submission prevention
86. Form data encryption (sensitive fields)
87. GDPR considerations en forms
88. Form localization (labels y mensajes multi-idioma)
89. Form theming (dark mode)
90. Dynamic forms (campos generados desde metadata)
91. Form builder pattern
92. JSON-driven forms
93. Form testing (unit tests)
94. Form testing (integration tests)
95. Selenium/E2E testing de forms
96. Form performance optimization
97. Formulario con conditional validation
98. Form con progressive disclosure
99. Formularios y accessibility audits
100. Best practices de UX en formularios ASP.NET

---

## MÓDULO 10: LAYOUTS, PARTIAL VIEWS Y ORGANIZACIÓN DE UI

**Descripción:** Aprenderás a organizar y reutilizar la interfaz de usuario en ASP.NET Core MVC. Dominarás layouts (plantillas maestras), partial views (fragmentos reutilizables), sections, View Components, y estrategias para mantener la UI limpia y mantenible en proyectos grandes.

1. ¿Qué es un Layout en ASP.NET Core?
2. `_Layout.cshtml`: estructura y contenido
3. `@RenderBody()` y su función
4. `_ViewStart.cshtml`: establecer layout por defecto
5. `Layout` property en vistas individuales
6. Cambiar layout por vista (`@{ Layout = "_OtherLayout"; }`)
7. `Layout = null` (vista sin layout)
8. Nested layouts (layout dentro de layout)
9. Sections: definir contenido opcional en layouts
10. `@section Scripts { }` y `@section Styles { }`
11. `@RenderSection("name")`
12. `@RenderSection("name", required: false)`
13. `@RenderSectionAsync("name")`
14. Secciones requeridas vs opcionales
15. Partial Views: concepto y cuándo usarlas
16. Crear una Partial View (`_Nombre.cshtml`)
17. `<partial name="_Partial" />` Tag Helper
18. `@await Html.PartialAsync("_Partial", model)`
19. `@await Html.PartialAsync("_Partial")` (sin modelo)
20. Diferencia entre `<partial>` Tag Helper y `Html.PartialAsync`
21. Partial Views con datos del padre
22. Partial Views con ViewData
23. Naming conventions para partials (`_` prefix)
24. Organizar partials por feature o por shared
25. View Components: qué son y por qué existen
26. View Component class: heredar de `ViewComponent`
27. `[ViewComponent]` attribute
28. `InvokeAsync` method
29. `IViewComponentResult`: `View()`, `Content()`, `Json()`
30. View Component con parámetros
31. Default view: `Views/Shared/Components/{Name}/Default.cshtml`
32. Custom view name para View Components
33. `<vc:name param="value" />` Tag Helper
34. `@await Component.InvokeAsync("Name", new { param = value })`
35. View Components con DI
36. View Components con async operations
37. View Components testing
38. Partial Views vs View Components: cuándo usar cada uno
39. Child Actions en MVC 5 (legado) vs View Components
40. Organización de carpetas en proyectos grandes
41. Feature folders: agrupar por funcionalidad
42. `Areas` para módulos grandes
43. Shared views en Areas
44. View discovery order
45. Custom view engine (IViewEngine)
46. View location formats
47. `IViewLocationExpander`
48. Custom view location con areas
49. Layout con navegación dinámica
50. Navigation menu como View Component
51. Breadcrumb como View Component
52. Sidebar como Partial View
53. Footer como Partial View
54. Header con login info como View Component
55. Notifications/toasts como Partial View
56. Modal dialogs como Partial Views
57. Layout responsive con Bootstrap
58. Multiple layouts (admin vs público)
59. Layout selection dinámico (por rol, por tenant)
60. Theme system con layouts
61. CSS isolation en Razor Pages (scoped CSS)
62. Static files organization en wwwroot
63. CSS architecture (BEM, utility classes)
64. JavaScript modules en vistas
65. Script management: `@section Scripts`
66. CDN management con Environment Tag Helper
67. Versioning de assets (`asp-append-version`)
68. Bundleconfig.json (legacy)
69. Libman.json para client-side libraries
70. Loading indicators como partials
71. Error boundaries como partials
72. Pagination como View Component o Partial
73. Search box como Partial View
74. User avatar como View Component
75. Tag cloud como View Component
76. Social sharing buttons como Partial View
77. Cookie consent banner como Partial View
78. GDPR consent como Partial View
79. Maintenance mode banner como Partial View
80. Language selector como View Component
81. Theme switcher como View Component
82. Dashboard cards como View Components
83. Charts como View Components (Chart.js integration)
84. DataTable partial con sorting/paging
85. Form components reutilizables
86. Input groups reutilizables
87. Address form como Editor Template
88. Date picker reusable component
89. File upload reusable component
90. Rich text editor reusable component
91. SEO metadata management en layout
92. Open Graph tags en layout
93. Twitter Card tags en layout
94. Structured data (JSON-LD) en layout
95. Favicon management
96. Apple touch icons
97. PWA manifest en layout
98. Layout y render performance
99. Caching de partials y view components
100. Testing de layouts y partials

---

## MÓDULO 11: ENTITY FRAMEWORK CORE – FUNDAMENTOS

**Descripción:** Aprenderás a usar Entity Framework Core (EF Core) como ORM para interactuar con bases de datos desde ASP.NET Core. Cubriremos desde la configuración inicial hasta consultas básicas, creación de DbContext, entidades, y las primeras operaciones CRUD contra una base de datos real.

1. ¿Qué es un ORM? ¿Qué es Entity Framework Core?
2. EF Core vs EF 6 (Framework)
3. Code-first vs Database-first
4. Instalación de EF Core NuGet packages
5. `Microsoft.EntityFrameworkCore`
6. `Microsoft.EntityFrameworkCore.SqlServer`
7. `Microsoft.EntityFrameworkCore.Tools`
8. `Microsoft.EntityFrameworkCore.Design`
9. DbContext: concepto y creación
10. Heredar de `DbContext`
11. `OnConfiguring` method (para connection string)
12. `OnModelCreating` method (para configuración)
13. Connection strings en `appsettings.json`
14. Registrar DbContext con DI: `AddDbContext<T>`
15. `DbContextOptions<T>`
16. Entity classes (POCO)
17. `DbSet<T>` y su relación con tablas
18. Naming conventions de EF Core (tablas, columnas)
19. Conventions de EF Core (primary keys por convención)
20. Data Annotations: `[Table]`, `[Column]`, `[Key]`
21. `[Required]`, `[StringLength]`, `[MaxLength]`
22. `[NotMapped]`
23. `[DatabaseGenerated]` (Identity, Computed, None)
24. `[Timestamp]` para concurrencia
25. Fluent API: `modelBuilder.Entity<T>()`
26. `.ToTable("NombreTabla")`
27. `.Property(e => e.Nombre).HasColumnName("nombre")`
28. `.Property(e => e.Nombre).HasMaxLength(200)`
29. `.Property(e => e.Nombre).IsRequired()`
30. `.HasKey(e => e.Id)`
31. `.HasAlternateKey(e => e.Email)`
32. Composite keys con Fluent API
33. `.HasIndex(e => e.Email).IsUnique()`
34. `.HasIndex(e => new { e.Apellido, e.Nombre })`
35. Querying data: `context.Productos.ToList()`
36. `context.Productos.FindAsync(id)`
37. `context.Productos.FirstOrDefault(e => e.Id == id)`
38. `context.Productos.Where(e => e.Precio > 100)`
39. `context.Productos.Count()`
40. `context.Productos.Any(e => e.Activo)`
41. Adding data: `context.Productos.Add(producto)`
42. `context.SaveChangesAsync()`
43. Updating data: `context.Productos.Update(producto)`
44. Deleting data: `context.Productos.Remove(producto)`
45. Change tracking en EF Core
46. `Entry(producto).State = EntityState.Modified`
47. Attach vs Add
48. Detached entities
49. `AsNoTracking()` para queries de solo lectura
50. Asynchronous operations: `ToListAsync`, `SaveChangesAsync`
51. Relaciones: One-to-Many (convention)
52. Relaciones: One-to-One
53. Relaciones: Many-to-Many
54. Foreign keys y navigation properties
55. Eager loading: `.Include(e => e.Categoria)`
56. `.ThenInclude(e => e.SubPropiedad)`
57. Lazy loading (habilitar con proxies)
58. Explicit loading: `Entry(entity).Collection(e => e.Items).Load()`
59. Projections con `Select` (anonymous types, DTOs)
60. Filtering, sorting, paging con LINQ
61. `OrderBy`, `OrderByDescending`, `ThenBy`
62. `Skip`, `Take` para paginación
63. `GroupBy` y aggregates
64. Raw SQL: `context.Productos.FromSqlRaw("SELECT * FROM Productos")`
65. `FromSqlInterpolated` para parámetros seguros
66. ExecuteSqlRaw para comandos
67. Views de base de datos con EF Core
68. Stored procedures con EF Core
69. Transactions: `context.Database.BeginTransaction()`
70. `IDbContextTransaction`
71. Savepoints en transacciones
72. Global query filters
73. Query types (keyless entities)
74. Owned entity types
75. Table-per-hierarchy (TPH) inheritance
76. Table-per-type (TPT) inheritance
77. Table-per-concrete-type (TPC) inheritance
78. Value conversions
79. `HasConversion` para enums como strings
80. Shadow properties
81. Backing fields
82. Alternate keys
83. Cascade delete behavior
84. Restrict, Cascade, SetNull, NoAction
85. Delete behaviors configurados con Fluent API
86. Seed data: `.HasData()`
87. EF Core logging de queries SQL
88. `ILoggerFactory` en DbContext
89. Sensitivity logging
90. Interceptors: `DbCommandInterceptor`
91. SaveChanges interceptor
92. Diagnostic listeners
93. Performance de queries (N+1 problem)
94. Split queries (`.AsSplitQuery()`)
95. Single vs Split query
96. Compiled queries
97. `DbContextPooling`
98. Connection resiliency y retry logic
99. EF Core y Azure SQL
100. EF Core versiones y novedades recientes

---

## MÓDULO 12: LINQ Y CONSULTAS AVANZADAS

**Descripción:** Profundizarás en LINQ (Language Integrated Query), la base de todas las consultas que harás con Entity Framework Core. Dominarás operadores de filtrado, proyección, ordenamiento, agrupamiento, joins, y cómo LINQ se traduce a SQL.

1. ¿Qué es LINQ? Sintaxis de consulta vs sintaxis de métodos
2. LINQ to Objects vs LINQ to Entities
3. `IEnumerable<T>` vs `IQueryable<T>`
4. Diferencia fundamental: client-side vs server-side evaluation
5. Deferred execution vs immediate execution
6. `Where` – filtrado
7. `Select` – proyección
8. `SelectMany` – aplanar colecciones
9. `OrderBy` / `OrderByDescending`
10. `ThenBy` / `ThenByDescending`
11. `Take` y `Skip` – paginación
12. `TakeWhile` y `SkipWhile`
13. `Distinct` y `DistinctBy`
14. `Union`, `Intersect`, `Except`
15. `Concat`
16. `First`, `FirstOrDefault`
17. `Last`, `LastOrDefault`
18. `Single`, `SingleOrDefault`
19. `Any` – verificar existencia
20. `All` – verificar universalidad
21. `Count`, `LongCount`
22. `Sum`, `Average`, `Min`, `Max`
23. `Aggregate` – acumulación personalizada
24. `Contains` y `Contains` con IEqualityComparer
25. `GroupBy` – agrupamiento
26. GroupBy con resultado personalizado
27. GroupBy con aggregates
28. `GroupJoin` – join con agrupamiento
29. `Join` – inner join
30. `Left join` con GroupJoin + SelectMany
31. Cross join con SelectMany
32. `Zip` – combinar dos secuencias
33. `OfType<T>` – filtrar por tipo
34. `Cast<T>` – convertir tipos
35. `AsEnumerable()` – forzar client-side
36. `AsQueryable()` – convertir a IQueryable
37. `ToList()`, `ToArray()`, `ToDictionary()`, `ToHashSet()`
38. `ToLookup()`
39. `ElementAt`, `ElementAtOrDefault`
40. `DefaultIfEmpty`
41. `Empty`, `Range`, `Repeat` (generadores)
42. `SequenceEqual`
43. `ExceptBy`, `IntersectBy`, `UnionBy` (.NET 6)
44. `Chunk` (.NET 6)
45. `MinBy`, `MaxBy` (.NET 6)
46. `DistinctBy` (.NET 6)
47. `Order`, `OrderDescending` (.NET 7)
48. `AggregateBy` (.NET 9)
49. Expression trees y `IQueryable`
50. `Func<T, bool>` vs `Expression<Func<T, bool>>`
51. Por qué las expresiones se traducen a SQL
52. LINQ queries que no se pueden traducir a SQL
53. `IQueryable` composition (queries dinámicas)
54. LINQ dinámico con System.Linq.Dynamic.Core
55. Paginación con LINQ (Skip/Take + Count)
56. Paginación y total count en una sola query
57. Filtering dinámico (múltiples filtros opcionales)
58. Sorting dinámico (ordenar por campo seleccionado)
59. Search con múltiples campos
60. LINQ con DateTime (Date comparisons)
61. LINQ con strings (`Contains`, `StartsWith`, `EndsWith`)
62. Case-insensitive searches
63. LINQ con nullables
64. EF.Functions: `Like`, `DateDiffDay`, `FreeText`
65. `EF.Functions.Contains` para Full-Text Search
66. Subqueries con LINQ
67. Any en subqueries (EXISTS en SQL)
68. All en subqueries
69. Contains en subqueries (IN en SQL)
70. Join con múltiples condiciones
71. Group join para left joins
72. Navigations properties en joins implícitos
73. Projections a DTOs
74. Projections a tipos anónimos (cuidado con serialización)
75. Projections con calculated fields
76. Projections con nested objects
77. GroupBy con multiple keys
78. GroupBy y projection a DTO con lista
79. LINQ performance considerations
80. Evitar N+1 con Include y ThenInclude
81. AsSplitQuery para Include múltiple
82. Compiled LINQ queries
83. `IQueryable` y unit of work pattern
84. Repositories que retornan IQueryable (pros y contras)
85. Specifications pattern
86. LINQ con stored procedures
87. LINQ y full-text search
88. LINQ y JSON columns (EF Core 7+)
89. LINQ temporal tables
90. Query tags (`TagWith`)
91. SQL generado por LINQ: cómo verlo
92. LINQPad como herramienta de aprendizaje
93. LINQ y performance: índices y query plans
94. Avoid client-side evaluation warnings
95. LINQ con projections y no-tracking
96. Materialization: cuándo se ejecuta la query
97. IQueryable leaks (cuidado con queries no materializadas)
98. Testing LINQ queries
99. Mocking IQueryable
100. Best practices de LINQ en aplicaciones reales

---

## MÓDULO 13: MIGRACIONES Y GESTIÓN DE BASE DE DATOS

**Descripción:** Aprenderás a gestionar el esquema de tu base de datos usando migraciones de EF Core. Desde la creación de la primera migración hasta la actualización, reversión, y estrategias de deployment de cambios de esquema en entornos reales.

1. ¿Qué son las migraciones en EF Core?
2. Code-first: flujo de trabajo completo
3. `Add-Migration` (Package Manager Console)
4. `dotnet ef migrations add` (CLI)
5. Estructura de una migración: `Up` y `Down`
6. Creación de tablas en migraciones
7. Agregar columnas
8. Renombrar columnas
9. Eliminar columnas
10. Cambiar tipos de columnas
11. Agregar índices
12. Agregar foreign keys
13. Agregar datos iniciales (seed data en migración)
14. `Update-Database` / `dotnet ef database update`
15. Aplicar migración específica
16. Revertir migración: `Update-Database MigrationName`
17. `Remove-Migration` / `dotnet ef migrations remove`
18. Script SQL de migración: `Script-Migration`
19. `dotnet ef migrations script`
20. Script desde migración específica hasta otra
21. Script idempotent (`--idempotent`)
22. Múltiples DbContext y migraciones
23. `--context` flag
24. Migrations folder organization
25. Migrations en equipo (merge conflicts)
26. Migrations en CI/CD
27. Migrations y producción: estrategias
28. Apply migrations at startup (`context.Database.Migrate()`)
29. ¿Por qué no aplicar migraciones automáticamente en producción?
30. Migrations con SQL Server
31. Migrations con PostgreSQL (Npgsql)
32. Migrations con SQLite
33. Migrations con MySQL/MariaDB
34. Migrations con in-memory provider (testing)
35. Custom migrations: operaciones SQL personalizadas
36. `migrationBuilder.Sql("...")`
37. `migrationBuilder.AddColumn` con SQL default
38. Renombrar tablas con `migrationBuilder.RenameTable`
39. Migraciones con datos sensibles
40. Migrations y GDPR (anonymization scripts)
41. Data seeding con `HasData`
42. Seed data y migraciones
43. Snapshot de modelo: `ModelSnapshot.cs`
44. `Designer.cs` en migraciones
45. Custom history table
46. `IHistoryRepository`
47. Migrations y columnas computed
48. Migrations y temporal tables
49. Database-first: `Scaffold-DbContext`
50. `dotnet ef dbcontext scaffold`
51. Scaffold con Data Annotations vs Fluent API
52. Scaffold y re-scaffold
53. Scaffold y stored procedures
54. Database-first: actualizar modelo desde DB
55. `--force` flag en scaffold
56. `--data-annotations` flag
57. `--context` para nombre de DbContext
58. `--output-dir` para directorio de entidades
59. Partial classes para extender entidades scaffolded
60. Database creation strategies
61. `EnsureCreated()` vs `Migrate()`
62. `EnsureCreated` para testing
63. `EnsureDeleted()` y `EnsureCreated()` para tests
64. Connection string management en migraciones
65. Migrations con Docker
66. Migrations con Azure SQL
67. Migrations y Entity Framework Power Tools
68. EF Core migrations bundles (self-contained)
69. `dotnet ef migrations bundle`
70. Migrations rollback strategies
71. Migrations y zero-downtime deployment
72. Expand-contract migration pattern
73. Additive-only migrations
74. Migrations review process
75. Migrations y version control
76. Custom `IMigrationAssembly`
77. Migrations con schemas (multiple schemas)
78. Migrations y table partitioning
79. Migrations y stored procedures management
80. Migrations y views management
81. Migrations y triggers
82. Migrations y full-text indexes
83. Migrations y sequences
84. Migrations y default values
85. Migrations y computed columns
86. Migrations y JSON columns
87. Migrations y spatial data
88. Migrations y hierarchid data
89. Redgate SQL Compare como alternativa
90. DbUp como alternativa a EF migrations
91. Flyway como alternativa
92. Liquibase como alternativa
93. Database project (dacpac) con SSDT
94. EF Core migrations vs dacpac
95. Backup y restore strategies
96. Point-in-time recovery
97. Database monitoring
98. Query performance y execution plans
99. Index optimization
100. Database migration testing strategies

---

## MÓDULO 14: DEPENDENCY INJECTION EN ASP.NET CORE

**Descripción:** Dominarás el sistema de Dependency Injection integrado en ASP.NET Core, uno de los pilares del framework. Aprenderás los conceptos de Inversión de Control, los ciclos de vida de los servicios, cómo registrar y resolver dependencias, y patrones avanzados de DI.

1. ¿Qué es Inversión de Control (IoC)?
2. ¿Qué es Dependency Injection (DI)?
3. Principio de Inversión de Dependencias (DIP)
4. ¿Por qué DI? (testabilidad, desacoplamiento, mantenibilidad)
5. Service Locator pattern vs Dependency Injection
6. Constructor injection (el patrón principal)
7. Property injection (menos común en ASP.NET Core)
8. Method injection
9. El contenedor de DI integrado en ASP.NET Core
10. `IServiceCollection` y `IServiceProvider`
11. `services.AddTransient<T>()`
12. `services.AddScoped<T>()`
13. `services.AddSingleton<T>()`
14. Diferencias entre Transient, Scoped, Singleton
15. Transient: nueva instancia cada vez
16. Scoped: una instancia por request HTTP
17. Singleton: una instancia para toda la vida de la app
18. Registro con interfaz y implementación: `AddTransient<ICat, Cat>()`
19. Registro con factory: `AddTransient<T>(sp => new T())`
20. Registro con instancia existente: `AddSingleton<T>(instance)`
21. Registrar múltiples implementaciones de la misma interfaz
22. Resolver `IEnumerable<T>` para obtener todas las implementaciones
23. `GetService<T>()` y `GetRequiredService<T>()`
24. `IServiceProvider.GetServices<T>()`
25. Inyección en constructors de Controllers
26. Inyección en Razor Views con `@inject`
27. Inyección en Middleware
28. Inyección en Filtros (ServiceFilter, TypeFilter)
29. Inyección en View Components
30. Inyección en `Program.cs` (endpoint handlers)
31. Inyección en Background Services
32. Dependency scopes y request lifetime
33. Scope validation en development
34. Captive dependency problem (Singleton que depende de Scoped)
35. `CreateScope()` para crear scopes manuales
36. `IServiceScopeFactory`
37. `IServiceScope` y `IDisposable`
38. Scoped services y background tasks (problema común)
39. `IServiceScopeFactory` en hosted services
40. `HttpClient` con DI: `AddHttpClient`
41. `IHttpClientFactory` y DI
42. Named clients con `IHttpClientFactory`
43. Typed clients con `IHttpClientFactory`
44. Options pattern y DI: `IOptions<T>`, `IOptionsSnapshot<T>`, `IOptionsMonitor<T>`
45. Registrar Options con `services.Configure<T>()`
46. Options validation con `ValidateDataAnnotations()`
47. Options validation con `Validate()`
48. Named options: `IOptionsSnapshot<T>`
49. Keyed services (.NET 8): `AddKeyedTransient`
50. `[FromKeyedServices("name")]`
51. `IKeyedServiceProvider`
52. Decorator pattern con DI
53. Implementar decorator sin librería externa
54. Scrutor library para decorator pattern
55. Open generic registrations: `AddTransient(typeof(IRepository<>), typeof(Repository<>))`
56. Generic constraints en DI registrations
57. `ActivatorUtilities.CreateInstance`
58. `ActivatorUtilities.GetServiceOrCreateInstance`
59. Anti-pattern: Service Locator
60. Anti-pattern: new keyword en controllers
61. Anti-pattern: Static dependencies
62. `IServiceProvider` como Service Locator (cuándo es aceptable)
63. DI y unit testing
64. Mocking dependencies con Moq
65. Mocking dependencies con NSubstitute
66. Crear un contenedor de DI propio (entendimiento)
67. Autofac como alternativa a contenedor built-in
68. Ninject como alternativa (legacy)
69. Simple Injector como alternativa
70. Castle Windsor como alternativa
71. Composite pattern con DI
72. Chain of responsibility con DI
73. Strategy pattern con DI
74. Factory pattern con DI
75. DI y arquitectura limpia (Clean Architecture)
76. DI y capas de la aplicación
77. DI y domain services
78. DI y application services
79. DI y infrastructure services
80. DI y cross-cutting concerns
81. DI y module registration (extension methods)
82. `AddMyModule(this IServiceCollection services)`
83. Service registration conventions
84. Assembly scanning para DI (Scrutor)
85. `services.Scan(scan => scan.FromAssemblyOf<T>())`
86. DI y performance
87. Compiled expressions para resolución rápida
88. `IServiceProviderIsService` para verificar si un servicio está registrado
89. `IServiceProviderIsService` en .NET 8
90. DI en Minimal APIs
91. DI en endpoint filters
92. DI y `IHost` vs `IHostBuilder` vs `WebApplicationBuilder`
93. DI y configuration (ApplicationBuilder pattern)
94. Testing con DI container
95. Integration testing y DI
96. Test-specific service registration
97. Replace services en tests
98. DI y logging
99. DI y middleware pipeline
100. Best practices de DI en ASP.NET Core

---

## MÓDULO 15: MIDDLEWARE PIPELINE EN ASP.NET CORE

**Descripción:** Comprenderás profundamente cómo funciona el pipeline de middleware en ASP.NET Core, el mecanismo que procesa cada solicitud HTTP. Aprenderás el orden de los middlewares, cómo crear los tuyos, y cómo se integran conceptos como authentication, routing, y endpoints en el pipeline.

1. ¿Qué es un middleware?
2. El pipeline de solicitud en ASP.NET Core
3. Request delegates y `RequestDelegate`
4. `app.Run()` – terminal middleware
5. `app.Use()` – middleware con next
6. `app.Map()` – branch por path
7. `app.MapWhen()` – branch condicional
8. `app.UseWhen()` – branch condicional sin rejoin
9. `app.UseMiddleware<T>()`
10. Inline middleware con `app.Use(async (context, next) => ...)`
11. `HttpContext`: Request, Response, Items, User
12. Short-circuiting el pipeline
13. Order matters: el orden de los middlewares es crítico
14. `app.UseExceptionHandler()`
15. `app.UseHsts()`
16. `app.UseHttpsRedirection()`
17. `app.UseStaticFiles()`
18. `app.UseRouting()`
19. `app.UseCors()`
20. `app.UseAuthentication()`
21. `app.UseAuthorization()`
22. `app.UseEndpoints()`
23. `app.MapControllers()`
24. `app.MapRazorPages()`
25. `app.MapBlazorHub()`
26. `app.MapHub<T>()` (SignalR)
27. `app.MapGet()`, `app.MapPost()`, etc.
28. `app.UseResponseCaching()`
29. `app.UseResponseCompression()`
30. `app.UseSession()`
31. `app.UseRequestLocalization()`
32. `app.UseStatusCodePages()`
33. `app.UseDeveloperExceptionPage()`
34. Middleware personalizado como clase
35. `IMiddleware` interface
36. Middleware per-request vs singleton middleware
37. `InvokeAsync` method
38. Constructor injection en middleware
39. Per-request services en middleware singleton (problema)
40. `HttpContext.Items` para pasar datos entre middleware
41. Middleware con parámetros (factory pattern)
42. Convention-based middleware (`Invoke`/`InvokeAsync`)
43. Factory-based middleware (`IMiddleware`)
44. Diferencia entre middleware y filtros
45. Middleware de logging personalizado
46. Middleware de timing (medir duración de request)
47. Middleware de correlation ID
48. Middleware de custom headers
49. Middleware de IP filtering
50. Middleware de request throttling
51. Middleware de maintenance mode
52. Middleware de request/response body reading
53. `Request.EnableBuffering()`
54. Request body rewind
55. Response body interception
56. Middleware de response wrapping
57. Pipeline de terminales y `app.Run()`
58. Branching por convención de ruta (`app.Map`)
59. `Map("/api", apiApp => { ... })`
60. `app.Use` vs `app.Map` vs `app.Run`
61. Middleware de diagnostic source
62. `DiagnosticSource` y `DiagnosticListener`
63. Middleware de request culture
64. `RequestLocalizationOptions`
65. Culture providers (query string, cookie, header)
66. Middleware de response caching
67. `ResponseCachingOptions`
68. `VaryByQueryKeys`, `VaryByHeaders`
69. `Cache-Control` headers
70. `app.UseResponseCompression()`
71. Gzip, Brotli compression providers
72. Custom compression
73. Middleware de health checks
74. `app.MapHealthChecks("/health")`
75. Health check UI
76. Middleware de output caching (.NET 7)
77. `app.UseOutputCache()`
78. Output cache policies
79. `app.UseRateLimiter()` (.NET 7)
80. Rate limiter strategies (fixed window, sliding window, token bucket)
81. `app.UseHttpLogging()`
82. W3C logging middleware
83. Forwarded headers middleware
84. `app.UseForwardedHeaders()`
85. Proxy y load balancer headers (X-Forwarded-For, X-Forwarded-Proto)
86. `app.UsePathBase()` para apps en subdirectorio
87. `app.UseWhen` con branching conditional
88. Middleware pipeline testing
89. `WebApplicationFactory` para integration tests
90. Middleware y performance
91. Middleware ordering best practices
92. Middleware vs Filters: cuándo usar cada uno
93. Middleware y dependency injection
94. Middleware y error handling
95. Middleware y logging
96. Middleware y security headers
97. `app.UseAntiforgery()` (.NET 8)
98. Middleware de request decompression
99. Endpoint middleware (delegates en endpoints)
100. Middleware pipeline en Minimal APIs vs MVC

---

## MÓDULO 16: CONFIGURACIÓN Y OPTIONS PATTERN

**Descripción:** Aprenderás cómo ASP.NET Core maneja la configuración de aplicaciones. Dominarás `appsettings.json`, variables de entorno, user secrets, el Options Pattern para tipar la configuración, y cómo crear configuraciones seguras y flexibles para diferentes entornos.

1. `appsettings.json`: estructura y formato
2. `appsettings.Development.json`
3. `appsettings.Production.json`
4. Jerarquía de configuración y override
5. `IConfiguration` e `IConfigurationRoot`
6. `IConfigurationSection`
7. `Configuration["Key"]` (acceso por clave)
8. `Configuration.GetSection("Section")`
9. `GetValue<T>("Key")`
10. `GetSection("Key").Get<T>()`
11. `Get<T>()` para mapear a objetos
12. Bind: `Configuration.Bind(obj)`
13. JSON nesting y secciones anidadas
14. Arrays en `appsettings.json`
15. Configuration providers en .NET
16. JsonConfigurationProvider
17. EnvironmentVariablesConfigurationProvider
18. CommandLineConfigurationProvider
19. UserSecretsConfigurationProvider
20. InMemoryConfigurationProvider
21. XmlConfigurationProvider
22. IniConfigurationProvider
23. Key-per-file provider
24. Azure App Configuration provider
25. Order de precedencia de providers
26. `AddJsonFile` con optional y reloadOnChange
27. `AddEnvironmentVariables()` y prefijos
28. `AddCommandLine(args)`
29. User Secrets: `dotnet user-secrets init`
30. `dotnet user-secrets set "Key" "Value"`
31. User secrets en desarrollo y cuándo se ignoran
32. Connection strings: proveedor específico
33. `ConnectionStrings:DefaultConnection`
34. Options Pattern: ¿por qué existe?
35. `IOptions<T>`: singleton, no cambia en runtime
36. `IOptionsSnapshot<T>`: scoped, se relee por request
37. `IOptionsMonitor<T>`: singleton, notifica cambios
38. `services.Configure<T>(Configuration.GetSection("T"))`
39. `services.Configure<T>(options => { ... })`
40. `services.AddOptions<T>().Bind(...)`
41. Named options: `IOptionsSnapshot<T>(name)`
42. `services.Configure<T>("name", section)`
43. Options validation: `ValidateDataAnnotations()`
44. Options validation: `Validate(options => condition)`
45. `IValidateOptions`
46. `ValidateOnStart()` (.NET 8)
47. Post-configure: `PostConfigure<T>()`
48. Options default values: `services.Configure<T>(defaults)`
49. Hierarchical options (nested configuration classes)
50. Options con DI en controllers, services, middleware
51. Options con DI en minimal APIs
52. Configuration y environments (`ASPNETCORE_ENVIRONMENT`)
53. `IWebHostEnvironment`
54. `IHostEnvironment`
55. `app.Environment.IsDevelopment()`, `.IsProduction()`
56. Custom environments
57. Environment-specific appsettings
58. Environment variables como configuration
59. Secret management en producción (Azure Key Vault)
60. Azure Key Vault configuration provider
61. AWS Secrets Manager configuration provider
62. HashiCorp Vault integration
63. Configuration en Docker (env vars, volumes)
64. Configuration en Kubernetes (ConfigMaps, Secrets)
65. Sensitive data en configuration (¡nunca en código!)
66. Gitignore para appsettings y user secrets
67. ReloadOnChange y hot reload de configuración
68. `IOptionsMonitor<T>.OnChange(callback)`
69. Watchers de cambio de configuración
70. Composite configuration (múltiples fuentes combinadas)
71. Configuration en microservicios
72. Feature flags con configuration
73. `Microsoft.FeatureManagement`
74. Feature flags en Razor views
75. Feature flags en controllers
76. Feature flags y A/B testing
77. Configuration de logging en appsettings
78. Serilog configuration desde appsettings
79. NLog configuration desde appsettings
80. Configuration de CORS desde appsettings
81. Configuration de rate limiting desde appsettings
82. Configuration de caching desde appsettings
83. Configuration de email desde appsettings
84. Configuration de external APIs desde appsettings
85. Configuration de OAuth/OIDC desde appsettings
86. Custom configuration provider
87. `IConfigurationSource`
88. `IConfigurationProvider`
89. Configuration y TDD
90. Mock configuration en tests
91. `InMemoryCollection` para tests
92. Configuration en integration tests
93. Best practices de configuration
94. Configuration naming conventions
95. Strongly-typed configuration vs raw IConfiguration
96. When to use Options vs direct IConfiguration
97. Configuration documentation
98. Configuration migration entre entornos
99. Configuration y 12-Factor App
100. Configuration monitoring y alerts

---

## MÓDULO 17: LOGGING Y DIAGNÓSTICOS

**Descripción:** Aprenderás el sistema de logging integrado en ASP.NET Core, cómo usarlo efectivamente, cómo integrar proveedores como Serilog y NLog, y herramientas de diagnósticos para entender qué está pasando dentro de tu aplicación en producción.

1. `ILogger<T>`: la interfaz de logging fundamental
2. `LogInformation`, `LogWarning`, `LogError`, `LogCritical`, `LogDebug`, `LogTrace`
3. Niveles de log: Trace, Debug, Information, Warning, Error, Critical, None
4. Inyección de `ILogger<T>` en controllers
5. Inyección de `ILogger<T>` en servicios
6. Inyección de `ILogger<T>` en middleware
7. Logging en `Program.cs`
8. `builder.Logging`
9. Console logger provider
10. Debug logger provider
11. EventSource logger provider
12. EventLog logger provider (Windows)
13. Azure App Service logger
14. Application Insights logger
15. Configurar log levels por categoría
16. `Logging:LogLevel:Default` en appsettings
17. `Logging:LogLevel:Microsoft` y otros namespaces
18. Structured logging con templates: `logger.LogInformation("Usuario {UserId} accedió", id)`
19. Por qué structured logging > string interpolation
20. `LoggerMessage.Define` para high-performance logging
21. `[LoggerMessage]` source generator attribute (.NET 6)
22. Scopes en logging: `using (logger.BeginScope(...))`
23. Request logging scopes (correlation ID, user ID)
24. `Activity` y distributed tracing
25. `DiagnosticSource` y `DiagnosticListener`
26. `ILoggerFactory`
27. `ILoggerProvider`
28. Custom logger provider
29. Serilog: instalación y configuración
30. `Serilog.AspNetCore` NuGet package
31. `UseSerilog()` en Program.cs
32. Serilog sinks: Console, File, Seq, Elasticsearch, Application Insights
33. Serilog structured logging
34. Serilog enrichers: WithMachineName, WithThreadId, WithCorrelationId
35. Serilog `WriteTo` configuration
36. Serilog filters
37. Serilog rolling file sink
38. Serilog con JSON formatter
39. Seq como structured log server
40. NLog: instalación y configuración
41. `NLog.Web.AspNetCore`
42. NLog targets: File, Console, Database, Email
43. NLog layout renderers
44. NLog y structured logging
45. Log4Net en .NET (legacy, pero existe)
46. Application Insights: setup
47. Application Insights: telemetry
48. Application Insights: custom events
49. Application Insights: dependency tracking
50. OpenTelemetry en .NET
51. OpenTelemetry: traces, metrics, logs
52. `AddOpenTelemetry()` configuration
53. OTLP exporter
54. Jaeger como backend de traces
55. Zipkin como backend de traces
56. Grafana + Prometheus para metrics
57. `System.Diagnostics.Metrics` y meters
58. Custom metrics con `Meter` y `Counter`
59. Histograms y gauges
60. Health checks con logging
61. Exception logging automática
62. Unhandled exceptions y logging
63. `app.UseExceptionHandler` con logging
64. Logging de requests HTTP (`UseHttpLogging`)
65. W3C logging
66. Kestrel connection logging
67. EF Core query logging
68. EF Core sensitive data logging
69. Logging y performance (cómo el logging afecta el rendimiento)
70. Async logging (buffered logging)
71. Log sampling
72. Log retention policies
73. Log aggregation en microservicios
74. ELK Stack (Elasticsearch, Logstash, Kibana)
75. Grafana Loki como alternativa
76. Correlation ID pattern
77. Trace ID propagation entre servicios
78. Logging en background services
78. Logging en SignalR hubs
80. Logging y GDPR (no logear datos personales)
81. Sensitive data masking en logs
82. PII filtering en logs
83. Structured logging best practices
84. Log message naming conventions
85. Logging levels guidelines
86. Alertas basadas en logs
87. Dashboarding con logs
88. Distributed tracing en microservicios
89. W3C TraceContext propagation
90. Baggage en distributed tracing
91. Custom activities
92. Debugging con logs en desarrollo
93. Log-based debugging en producción
94. `dotnet-counters` tool
95. `dotnet-trace` tool
96. `dotnet-dump` tool
97. Diagnostic tools en .NET
98. EventPipe y EventCounters
99. Logging testing strategies
100. Best practices de logging en producción

---

## MÓDULO 18: MANEJO DE ERRORES Y EXCEPCIONES

**Descripción:** Aprenderás a implementar una estrategia robusta de manejo de errores en ASP.NET Core. Desde el middleware de excepciones global hasta filtros personalizados, Problem Details, error logging, y cómo presentar errores apropiadamente al usuario y al consumidor de APIs.

1. Excepciones en .NET: `try`, `catch`, `finally`, `throw`
2. `Exception` base class y propiedades (`Message`, `StackTrace`, `InnerException`)
3. Excepciones comunes: `NullReferenceException`, `ArgumentException`, `InvalidOperationException`
4. `HttpRequestException` para llamadas HTTP
5. `DbUpdateException` para errores de EF Core
6. Custom exceptions (heredar de `Exception`)
7. Exception hierarchies
8. `throw` vs `throw ex` (preserve stack trace)
9. Exception filters (C# 6): `catch (Exception ex) when (condition)`
10. `app.UseDeveloperExceptionPage()` en Development
11. `app.UseExceptionHandler()` en Production
12. `app.UseStatusCodePages()` para respuestas de status code
13. `app.UseStatusCodePagesWithRedirects("/error/{0}")`
14. `app.UseStatusCodePagesWithReExecute("/error/{0}")`
15. Páginas de error personalizadas (Error.cshtml)
16. Controller de error personalizado
17. Error model con mensaje y requestId
18. `IExceptionHandler` interface (.NET 8)
19. Exception handler middleware personalizado
20. `IProblemDetailsService` (.NET 8)
21. Problem Details (RFC 7807): formato estándar
22. `ProblemDetails` class en ASP.NET Core
23. `Results.Problem()` en Minimal APIs
24. `return Problem()` en Controllers
25. `ProblemDetails` customization
26. `IProblemDetailsWriter`
27. Problem Details con `AddProblemDetails()` (.NET 8)
28. `InvalidModelStateResponseFactory` para validation errors
29. Global exception filter en MVC
30. `IExceptionFilter` implementation
31. `ExceptionContext` y propiedades
32. Exception filter por controller o action
33. Exception filter global con `AddMvcOptions`
34. Exception handling en API controllers
35. Exception handling en MVC controllers (views)
36. Exception handling en Minimal APIs (endpoint filters)
37. Exception handling en middleware
38. Exception handling en background services
39. Exception handling en SignalR hubs
40. Logging de excepciones: qué logear y qué no
41. Structured exception logging
42. Exception ya manejada vs no manejada
43. `AppDomain.UnhandledException`
44. `TaskScheduler.UnobservedTaskException`
45. Unhandled exceptions en ASP.NET Core
46. Graceful degradation con exceptions
47. Retry patterns para errores transitorios
48. Polly para resilience: retry, circuit breaker
49. `Microsoft.Extensions.Http.Polly`
50. Circuit breaker pattern
51. Bulkhead isolation
52. Timeout con Polly
53. Polly v8 resilience pipelines
54. HTTP error handling en `HttpClient`
55. `HttpRequestException` y status codes
56. Custom error responses para API
57. Error codes y mensajes consistentes
58. API error response DTOs
59. Error handling y Content Negotiation
60. Error handling y CORS (errores no bloqueados por CORS)
61. Validation errors como ProblemDetails
62. Business logic exceptions vs infrastructure exceptions
63. Exception mapping: exception → HTTP response
64. Global error handling strategy
65. Sentry.io para error tracking
66. Bugsnag, Raygun, Rollbar como alternativas
67. Application Insights exception tracking
68. Error dashboards
69. Error alerting
70. Error rate monitoring
71. Health checks y error detection
72. Deadlock detection
73. Memory leak detection
74. `OutOfMemoryException` handling
75. `StackOverflowException` (no se puede catchear)
76. `OperationCanceledException` y `TaskCanceledException`
77. CancellationToken y graceful cancellation
78. Timeout exceptions
79. Connection string errors
80. Database connection failures
81. External API failures
82. File system errors (permissions, not found)
83. Serialization errors
84. Authentication/authorization errors
85. 401 vs 403: cuándo retornar cada uno
86. 404 handling: página personalizada
87. 429 Too Many Requests
88. 500 Internal Server Error
89. 502 Bad Gateway (proxy errors)
90. 503 Service Unavailable
91. Error handling testing
92. Unit testing exception scenarios
93. Integration testing error responses
94. Fault injection testing
95. Chaos engineering basics
96. Error handling documentation
97. Error codes documentation
98. Runbook para errores comunes
99. On-call y error response procedures
100. Best practices de error handling en producción

---

## MÓDULO 19: FILTROS EN ASP.NET CORE MVC

**Descripción:** Dominarás los filtros de ASP.NET Core MVC, que te permiten ejecutar código antes o después de etapas específicas del pipeline de ejecución de acciones. Aprenderás los cinco tipos de filtros, cómo crear filtros personalizados, y cuándo usar filtros vs middleware.

1. ¿Qué son los filtros en ASP.NET Core?
2. Los 5 tipos de filtros: Authorization, Resource, Action, Exception, Result
3. Orden de ejecución de filtros
4. Pipeline de filtros (onion model)
5. `IAuthorizationFilter` y su fase
6. `IResourceFilter` y su fase
7. `IActionFilter` y su fase
8. `IExceptionFilter` y su fase
9. `IResultFilter` y su fase
10. `IAsyncAuthorizationFilter`
11. `IAsyncResourceFilter`
12. `IAsyncActionFilter`
13. `IAsyncExceptionFilter`
14. `IAsyncResultFilter`
15. `IOrderedFilter` y el orden de ejecución
16. `Order` property en filtros
17. `IFilterMetadata` interface base
18. `ActionFilterAttribute` (combina Action y Result)
19. `ResultFilterAttribute`
20. `TypeFilterAttribute`
21. `ServiceFilterAttribute`
22. Diferencia entre `TypeFilter` y `ServiceFilter`
23. Filtros como attributes (decoradores)
24. `[ServiceFilter(typeof(MyFilter))]`
25. `[TypeFilter(typeof(MyFilter))]`
26. Filter scopes: Global, Controller, Action
27. Registering global filters en `AddMvcOptions`
28. `filters.Add(new MyGlobalFilter())`
29. Filtros y dependency injection
30. `ActionExecutingContext`
31. `ActionExecutedContext`
32. `ResultExecutingContext`
33. `ResultExecutedContext`
34. `ExceptionContext`
35. `AuthorizationFilterContext`
36. `ResourceExecutingContext`
37. `ResourceExecutedContext`
38. Short-circuiting en Action Filter
39. Short-circuiting en Authorization Filter
40. Short-circuiting en Resource Filter
41. Cancel result en filters
42. Log timing de acciones con Action Filter
43. Logging filter como TypeFilter
44. Custom authorization filter
45. Claims checking en authorization filter
46. IP filtering con authorization filter
47. Feature flags en authorization filter
48. Anti-forgery validation filter
49. Response caching filter
50. Response compression filter
51. Model validation filter (auto-validate)
52. `[AutoValidateAntiforgeryToken]`
53. `[IgnoreAntiforgeryToken]`
54. Exception filter: custom error pages
55. Exception filter: API error responses
56. Exception filter: logging y alerting
57. Result filter: modify response
58. Result filter: add headers
59. Result filter: transform JSON
60. Result filter: caching personalizado
61. Resource filter: model validation
62. Resource filter: request body reading
63. Resource filter: rate limiting
64. Filter factories: `IFilterFactory`
65. Custom filter factory
66. `IFilterFactory` con DI
67. Filtros en Razor Pages
68. `IPageFilter` y `IAsyncPageFilter`
69. `PageHandlerExecutingContext`
70. `PageHandlerExecutedContext`
71. Filtros en endpoint routing
72. Endpoint filters en Minimal APIs (.NET 7)
73. `IEndpointFilter`
74. `EndpointFilterInvocationContext`
75. Endpoint filter: validation
76. Endpoint filter: logging
77. Endpoint filter: response transformation
78. Endpoint filter: error handling
79. Override filters con `[OverrideActionFilters]`
80. Override authorization filters con `[OverrideAuthorization]`
81. Disable filters
82. Filtros y testing
83. Testing Action Filters
84. Testing Exception Filters
85. Testing Endpoint Filters
86. Mocking filter context
87. Filters vs Middleware: cuándo usar cada uno
88. Filters vs Attributes
89. Filters performance considerations
90. Filtros y cache
91. Response caching con filtros
92. Output caching con filtros
93. Filtros y versioning
94. Filtros y multi-tenancy
95. Filtros y localization
96. Filtros y rate limiting
97. Filtros y profiling
98. Concurrency filters
99. Circuit breaker en filtros
100. Best practices de filtros en ASP.NET Core

---

## MÓDULO 20: AUTENTICACIÓN CON COOKIES Y SESIONES

**Descripción:** Aprenderás los fundamentos de autenticación en ASP.NET Core usando cookies. Entenderás el sistema de identidad, claims, autenticación basada en cookies, sesiones, y cómo proteger tus controllers y acciones contra acceso no autorizado.

1. ¿Qué es autenticación vs autorización?
2. Claims-based identity en .NET
3. `ClaimsPrincipal` y `ClaimsIdentity`
4. `Claim` y tipos comunes (Name, Role, Email)
5. `HttpContext.User`
6. Authentication schemes
7. Cookie authentication: configuración
8. `AddAuthentication(CookieAuthenticationDefaults.AuthenticationScheme)`
9. `AddCookie()`
10. `CookieAuthenticationOptions`
11. `LoginPath`, `LogoutPath`, `AccessDeniedPath`
12. `Expiration` y `SlidingExpiration`
13. `Cookie.HttpOnly`, `Cookie.SecurePolicy`
14. `Cookie.SameSite`
15. Sign in con cookies: `HttpContext.SignInAsync()`
16. Sign out: `HttpContext.SignOutAsync()`
17. Crear `ClaimsPrincipal` con claims
18. `ClaimsIdentity` y `AuthenticationType`
19. `ClaimTypes` estándar (Name, Role, Email, NameIdentifier)
20. Custom claims
21. Claims serialization en cookies
22. `TicketDataFormat` para encrypt claims
23. Data Protection API (DPAPI) para cookies
24. `IDataProtectionProvider`
25. Custom data protector
26. `app.UseAuthentication()`
27. `app.UseAuthorization()`
28. `[Authorize]` attribute
29. `[AllowAnonymous]` attribute
30. `Authorize` en controller level
31. `Authorize` en action level
32. `Authorize` en Razor Pages
33. `Authorize` en Minimal APIs
34. `RequireAuthorization()` en endpoints
35. `Policy` property: `Authorize(Policy = "AdminOnly")`
36. `Roles` property: `Authorize(Roles = "Admin")`
37. Multiple roles: `Authorize(Roles = "Admin,Manager")`
38. Login form y POST handler
39. Validar credenciales (hardcoded, database, LDAP)
40. Password hashing con `PasswordHasher<T>`
41. BCrypt como alternativa
42. Registration flow
43. Logout flow
44. ReturnUrl handling
45. Anti-forgery tokens en login forms
46. Persistent cookies vs session cookies
47. Cookie events: `OnValidatePrincipal`
48. Refresh tokens en cookies
49. Sliding expiration
50. Absolute expiration
51. Cookie security: HttpOnly, Secure, SameSite
52. Session management en ASP.NET Core
53. `AddSession()` y `UseSession()`
54. `ISession` interface
55. `HttpContext.Session.SetString()`, `.GetString()`
56. Session state providers (in-memory, distributed)
57. Session y serialization
58. Session y cookies (session cookie)
59. Session timeout
60. Session y GDPR
61. Distributed session con Redis
62. Distributed session con SQL Server
63. `DistributedSession` y `IDistributedCache`
64. External authentication providers (Google, Facebook, Microsoft)
65. `AddGoogle()` authentication
66. `AddMicrosoftAccount()`
67. `AddFacebook()`
68. OAuth 2.0 flow básico
69. OpenID Connect básico
70. Sign in with external provider
71. Link external accounts
72. Multiple authentication schemes
73. `DefaultScheme` vs `DefaultChallengeScheme`
74. Policy schemes
75. Forwarding authentication schemes
76. Windows authentication (IIS, Kestrel)
77. NTLM / Kerberos authentication
78. Certificate authentication
79. API Key authentication
80. Custom authentication handler
81. `AuthenticationHandler<TOptions>`
82. `AuthenticateResult`
83. `HandleAuthenticateAsync()`
84. `HandleChallengeAsync()`
85. `HandleForbidAsync()`
86. Custom authentication scheme
87. Testing authentication
88. Mock authentication en integration tests
89. `AddAuthentication("Test")` para tests
90. Security best practices para cookies
91. OWASP top 10 y authentication
92. Brute force protection
93. Account lockout
94. Password policies
95. Two-factor authentication (2FA)
96. TOTP (Time-based One-Time Password)
97. Authenticator app setup
98. Recovery codes
99. Password reset flow
100. Email confirmation flow

---

## MÓDULO 21: ASP.NET CORE WEB API

**Descripción:** Aprenderás a construir APIs RESTful con ASP.NET Core. Desde la creación de un proyecto API hasta la implementación completa de endpoints que retornan JSON, manejo de status codes, content negotiation, y todas las convenciones de una API profesional.

1. Crear proyecto API: `dotnet new webapi`
2. Estructura del proyecto API
3. `Program.cs` en proyecto API
4. `app.MapControllers()`
5. `ApiController` attribute y sus efectos
6. `[ApiController]`: auto-validación, auto-problem details
7. Controllers: heredar de `ControllerBase`
8. `ControllerBase` vs `Controller`
9. `[Route("api/[controller]")]`
10. HTTP methods: `[HttpGet]`, `[HttpPost]`, `[HttpPut]`, `[HttpDelete]`, `[HttpPatch]`
11. Return types: `IActionResult`, `ActionResult<T>`, `T`
12. `Ok()` - 200
13. `Created()` - 201
14. `CreatedAtAction()` - 201 con Location header
15. `CreatedAtRoute()` - 201 con route name
16. `NoContent()` - 204
17. `BadRequest()` - 400
18. `NotFound()` - 404
19. `Unauthorized()` - 401
20. `Forbid()` - 403
21. `Conflict()` - 409
22. `UnprocessableEntity()` - 422
23. `StatusCode(500)` - custom status codes
24. `File()` para archivos
25. `PhysicalFile()` para archivos físicos
26. `VirtualFile()` para archivos virtuales
27. Model binding en APIs: `[FromBody]`, `[FromQuery]`, `[FromRoute]`, `[FromHeader]`
28. Implicit `[FromBody]` con `[ApiController]`
29. JSON serialization: System.Text.Json
30. `JsonSerializerOptions` (camelCase, null handling)
31. `JsonSerializerDefaults.Web`
32. Property naming policy
33. Null handling: `JsonIgnoreCondition`
34. `JsonPropertyName` attribute
35. `JsonIgnore` attribute
36. Polymorphic serialization (.NET 7)
37. `JsonDerivedType` attribute
38. Custom converters
39. `Newtonsoft.Json` como alternativa
40. Content negotiation: Accept header
41. `Produces` attribute: `Produces("application/json")]`
42. `ProducesResponseType` attribute: documentar status codes
43. `[ProducesResponseType(typeof(T), 200)]`
44. `[ProducesResponseType(StatusCodes.Status404NotFound)]`
45. Multiple ProducesResponseType
46. HATEOAS (concepto)
47. Pagination en APIs: `page`, `pageSize`, `totalItems`
48. Pagination response model
49. Filtering en APIs
50. Sorting en APIs
51. Searching en APIs
52. OData (concepto y configuración básica)
53. ActionResult<T> vs IActionResult: diferencias
54. `ActionResult<T>`: retorna T o ActionResult
55. API conventions: `ApiConventionMethod`
56. Default API conventions
57. Custom API conventions
58. `[Consumes]` attribute
59. Multiple content types support
60. Multipart/form-data en APIs
61. File upload API endpoint
62. File download API endpoint
63. Streaming large files
64. Range requests (partial content)
65. ETag y conditional requests
66. `If-None-Match`, `If-Modified-Since`
67. Response caching headers
68. `Location` header en 201 responses
69. API response envelope pattern
70. Envelope<T> wrapper
71. Error response standardization
72. ProblemDetails en APIs
73. Custom error codes
74. API pagination links (HATEOAS)
75. `Link` header para pagination
76. Compression de responses
77. Idempotency en APIs
78. ETags para optimistic concurrency
79. `If-Match` header para updates
80. DELETE idempotency
81. API rate limiting
82. CORS configuration para APIs
83. Swagger/OpenAPI (módulo siguiente)
84. Health check endpoints
85. Metadata endpoints
86. Controller naming conventions
87. Action naming conventions
88. Route naming conventions
89. API versioning (módulo futuro)
90. Typed results en Minimal APIs (módulo futuro)
91. Integration testing de APIs
92. Unit testing de API controllers
93. `WebApplicationFactory<T>` para tests
94. `HttpClient` en tests
95. Testing con in-memory database
96. API documentation
97. API design guidelines
98. REST maturity model (Richardson)
99. REST vs GraphQL vs gRPC: comparación
100. Best practices de API design

---

## MÓDULO 22: RESTful API DESIGN

**Descripción:** Aprenderás los principios de diseño de APIs RESTful. No solo es crear endpoints que retornan JSON, sino diseñar APIs consistentes, intuitivas, bien documentadas, y que sigan estándares de la industria.

1. ¿Qué es REST? (Representational State Transfer)
2. Los 6 principios de REST
3. Stateless: sin estado entre requests
4. Client-server: separación de responsabilidades
5. Cacheable: respuestas cacheables
6. Uniform Interface: convenciones consistentes
7. Layered System: capas intermedias
8. Code on Demand (opcional)
9. Resources y URLs: nouns, not verbs
10. Singular vs plural en URLs: `/productos` vs `/producto`
11. Nouns naming: lowercase, kebab-case o camelCase
12. Collection resources: `/api/productos`
13. Single resource: `/api/productos/{id}`
14. Sub-resources: `/api/productos/{id}/reviews`
15. Nested resources: limitar profundidad (máximo 2-3 niveles)
16. HTTP methods mapping:
17. GET → Read (list o get)
18. POST → Create
19. PUT → Replace (full update)
20. PATCH → Partial update
21. DELETE → Delete
22. Safe methods (GET, HEAD, OPTIONS)
23. Idempotent methods (GET, PUT, DELETE, HEAD, OPTIONS)
24. POST no es idempotente
25. PUT es idempotente
26. PATCH: idempotencia depende de implementación
27. Status codes usage guidelines:
28. 200 OK: successful GET, PUT, PATCH
29. 201 Created: successful POST
30. 204 No Content: successful DELETE
31. 301/302 Redirect
32. 400 Bad Request: validation errors
33. 401 Unauthorized: no autenticado
34. 403 Forbidden: no autorizado
35. 404 Not Found
36. 405 Method Not Allowed
37. 409 Conflict
38. 422 Unprocessable Entity
39. 429 Too Many Requests
40. 500 Internal Server Error
41. 503 Service Unavailable
42. Pagination: query parameters (`page`, `pageSize`)
43. Pagination: cursor-based
44. Pagination: offset-based
45. Pagination: Link header
46. Pagination: response envelope con `totalItems`, `totalPages`
47. Filtering: query parameters
48. Filtering: multiple values (`?status=active,pending`)
49. Filtering: ranges (`?price_min=10&price_max=100`)
50. Sorting: `?sort=name` y `?sort=-date` (desc prefix)
51. Sorting: multiple fields (`?sort=name,-date`)
52. Searching: `?q=searchterm`
53. Field selection: `?fields=name,price`
54. Sparse fieldsets
55. Expanding: `?expand=category,reviews`
56. HATEOAS: hyperlinks en responses
57. Link relations: self, next, prev, first, last
58. HAL (Hypertext Application Language)
59. JSON:API specification
60. Content negotiation: Accept header
61. Versioning: URL path (`/v1/productos`)
62. Versioning: query parameter (`?api-version=1.0`)
63. Versioning: header (`X-API-Version`)
64. Versioning: Accept header (`application/vnd.myapi.v1+json`)
65. Versioning strategy comparison
66. ETag para caching
67. `Cache-Control` headers
68. `Last-Modified` / `If-Modified-Since`
69. CORS: configuración para APIs
70. CORS: preflight requests (OPTIONS)
71. Rate limiting: strategies
72. Throttling: conceptos
73. API keys: usage y limitations
74. Bearer tokens: JWT
75. OAuth 2.0: flows overview
76. OpenID Connect: concepto
77. Error responses consistentes
78. ProblemDetails (RFC 7807)
79. Custom error codes
80. Validation errors format
81. Logging y monitoring de APIs
82. API gateway patterns
83. Backend for Frontend (BFF) pattern
84. Composite pattern (aggregate APIs)
85. API documentation: OpenAPI/Swagger
86. API changelog y deprecation
87. Sunset header
88. Deprecation header
89. API client SDK generation
90. Contract testing
91. Consumer-driven contracts
92. Pact for contract testing
93. API mocking para frontend teams
94. WireMock como mock server
95. API design tools (Stoplight, Swagger Editor)
96. API style guides (Google, Microsoft, Zalando)
97. API governance
98. API analytics
99. API security checklist
100. REST maturity model levels (0-3)

---

## MÓDULO 23: SWAGGER / OPENAPI

**Descripción:** Aprenderás a documentar y explorar tu API automáticamente con Swagger (OpenAPI). Configurarás Swagger UI para que cualquier desarrollador pueda entender y probar tu API sin leer una línea de código.

1. ¿Qué es OpenAPI Specification?
2. ¿Qué es Swagger? (Swagger = implementación de OpenAPI)
3. `Swashbuckle.AspNetCore` NuGet package
4. `AddEndpointsApiExplorer()`
5. `AddSwaggerGen()`
6. `UseSwagger()` y `UseSwaggerUI()`
7. Swagger UI: explorar endpoints
8. Swagger UI: probar endpoints (Try it out)
9. Swagger JSON endpoint: `/swagger/v1/swagger.json`
10. OpenAPI document customization
11. `SwaggerDoc` configuration: title, version, description
12. XML documentation comments (`/// <summary>`)
13. `<GenerateDocumentationFile>true</GenerateDocumentationFile>`
14. `IncludeXmlComments()`
15. `DescribeAllParametersInCamelCase()`
16. `[SwaggerOperation]` attribute
17. `[SwaggerResponse]` attribute
18. `[SwaggerTag]` attribute
19. `[SwaggerSchema]` attribute
20. Custom schema filters: `ISchemaFilter`
21. Custom operation filters: `IOperationFilter`
22. Custom document filters: `IDocumentFilter`
23. Add security definition (JWT Bearer)
24. `AddSecurityDefinition("Bearer", ...)`
25. `AddSecurityRequirement()`
26. API Key authentication en Swagger
27. OAuth 2.0 authentication en Swagger
28. Multiple authentication schemes en Swagger
29. Grouping endpoints por tags
30. Custom tag ordering
31. Endpoint descriptions desde XML comments
32. Parameter descriptions
33. Enum descriptions en Swagger
34. `[SwaggerEnum]` custom attribute
35. Hidden endpoints: `[ApiExplorerSettings(IgnoreApi = true)]`
36. Multiple API versions con Swagger
37. `AddSwaggerDoc` per version
38. Swagger UI: select version dropdown
39. `SwaggerGeneratorOptions`
40. `SwaggerGenOptions`
41. Polymorphic schemas en Swagger
42. `[JsonDerivedType]` y Swagger
43. File upload documentation
44. Multipart form documentation
45. Custom request example values
46. `[SwaggerRequestExample]`
47. Custom response examples
48. Swashbuckle.AspNetCore.Filters
49. Swagger y Minimal APIs
50. `.WithOpenApi()` en endpoints
51. OpenAPI metadata en Minimal APIs
52. `WithTags()`, `WithName()`, `WithDescription()`
53. `WithSummary()`
54. Request/Response examples con `.WithOpenApi()`
55. Swagger UI customization
56. Custom CSS para Swagger UI
57. Custom JavaScript para Swagger UI
58. Swagger UI: logo customization
59. Swagger UI: deep linking
60. Swagger UI: filter por tag
61. Swagger UI: persist authorization
62. NSwag como alternativa
63. NSwang: code generation
64. NSwag Studio
65. Kiota como alternativa (Microsoft)
66. OpenAPI 3.0 vs 3.1
67. Swagger 2.0 vs OpenAPI 3.0
68. $ref y reusable schemas
69. Reusable parameters
70. Reusable responses
71. Discriminator para polimorfismo
72. Webhooks en OpenAPI 3.1
73. Callbacks en OpenAPI
74. Links en OpenAPI
75. Server variables
76. Path item object
77. Components object
78. Schema object en detalle
79. Security schemes
80. Scopes
81. Bearer authentication scheme
82. API key authentication scheme
83. OAuth2 flows en OpenAPI
84. Client code generation desde OpenAPI
85. `openapi-generator` CLI
86. AutoRest (Microsoft)
87. NSwag code generation
88. TypeScript client generation
89. C# client generation
90. OpenAPI con API versioning
91. OpenAPI y response caching
92. OpenAPI y health checks
93. OpenAPI en producción: ¿dejarlo habilitado?
94. Security considerations de Swagger UI
95. Swagger y CORS
96. Swagger en reverse proxy (Nginx, IIS)
97. Swagger y authentication flow
98. Testing API con Swagger UI
99. OpenAPI linting (Spectral)
100. Best practices de API documentation

---

## MÓDULO 24: AUTENTICACIÓN JWT (JSON WEB TOKENS)

**Descripción:** Aprenderás a implementar autenticación basada en tokens JWT, el estándar para APIs modernas. Entenderás la estructura de un JWT, cómo generarlo, validarlo, refrescarlo, y cómo usarlo para proteger tus endpoints de API.

1. ¿Qué es un JWT (JSON Web Token)?
2. Estructura de un JWT: Header, Payload, Signature
3. Header: `alg` y `typ`
4. Payload: claims (iss, sub, aud, exp, iat, jti)
5. Registered claims, public claims, private claims
6. Signature: HMAC SHA256, RSA, ECDSA
7. JWT vs opaque tokens
8. Access tokens vs refresh tokens
9. `Microsoft.AspNetCore.Authentication.JwtBearer`
10. `AddJwtBearer()` configuration
11. `TokenValidationParameters`
12. `ValidateIssuer`, `ValidateAudience`, `ValidateLifetime`
13. `ValidIssuer`, `ValidAudience`
14. `IssuerSigningKey` y `SecurityKey`
15. `SymmetricSecurityKey` vs `AsymmetricSecurityKey`
16. `SigningCredentials`
17. Generar un JWT con `JwtSecurityTokenHandler`
18. `JwtSecurityToken` y `SecurityTokenDescriptor`
19. Agregar claims al token
20. Custom claims en JWT
21. Expire time configuración
22. Login endpoint que retorna JWT
23. `app.UseAuthentication()` y `app.UseAuthorization()`
24. `[Authorize]` en API endpoints
25. Bearer token en header: `Authorization: Bearer <token>`
26. Validate token en Swagger UI
27. Refresh token pattern
28. Refresh token: almacenamiento (database)
29. Refresh token: rotación
30. Refresh token: revocación
31. Token refresh endpoint
32. Sliding expiration con refresh tokens
33. Absolute expiration
34. Token blacklist
35. Token whitelist
36. JWT y CSRF (no vulnerable a CSRF pero sí a XSS)
37. JWT storage en cliente (localStorage vs memory vs HttpOnly cookie)
38. JWT en cookies: BFF pattern
39. JWT con role claims
40. JWT con policy claims
41. `[Authorize(Roles = "Admin")]` con JWT
42. Custom authorization con JWT claims
43. Token validation events: `OnTokenValidated`
44. Token validation events: `OnAuthenticationFailed`
45. Custom token validation
46. Multiple issuers
47. JWT y microservicios
48. Token propagation entre servicios
49. Opaque tokens + introspection
50. JWT vs session tokens
51. JWT y token size concerns
52. JWT y security best practices
53. Don't store sensitive data en JWT
54. Always validate signature
55. Always validate expiration
56. Use HTTPS
57. Rotate signing keys
58. Short-lived access tokens
59. Longer-lived refresh tokens
60. Key rotation strategy
61. JWKS (JSON Web Key Set) endpoint
62. `OpenIdConnectConfiguration`
63. Metadata endpoint
64. RSA keys para JWT
65. X509 certificates para JWT
66. Generating RSA key pairs
67. Key management
68. Azure Key Vault para keys
69. JWT con IdentityServer
70. JWT con Duende IdentityServer
71. JWT con Azure AD
72. JWT con Auth0
73. JWT con Firebase Auth
74. JWT y API Gateway
75. JWT validation en API Gateway (YARP)
76. JWT y SignalR authentication
77. JWT en WebSocket connections
78. JWT y OAuth 2.0
79. Client credentials flow
80. Authorization code flow
81. PKCE (Proof Key for Code Exchange)
82. Device code flow
83. Resource owner password flow (legacy)
84. Implicit flow (deprecated)
85. JWT con Minimal APIs
86. JWT en endpoint filters
87. JWT testing
88. Mock JWT en tests
89. Generate test tokens
90. `TestAuthHandler` para integration tests
91. JWT token inspection tools (jwt.io)
92. JWT y logging
93. JWT y rate limiting
94. JWT y account lockout
95. JWT y multi-factor authentication
96. JWT y claim-based authorization
97. JWT y tenant resolution
98. JWT revocation patterns
99. JWT y API key como alternativa
100. Best practices de JWT en producción

---

## MÓDULO 25: AUTORIZACIÓN: POLICIES Y ROLES

**Descripción:** Profundizarás en el sistema de autorización de ASP.NET Core, que va mucho más allá de simple verificación de roles. Aprenderás policy-based authorization, claims-based authorization, resource-based authorization, y custom authorization handlers.

1. Autorización: conceptos fundamentales
2. Authentication vs Authorization
3. Role-based authorization: `[Authorize(Roles = "Admin")]`
4. Multiple roles: `Roles = "Admin,Manager"`
5. `User.IsInRole("Admin")`
6. Policy-based authorization: `[Authorize(Policy = "RequireAdmin")]`
7. `AddAuthorization(options => options.AddPolicy(...))`
8. `RequireRole()` en policies
9. `RequireClaim()` en policies
10. `RequireAuthenticatedUser()`
11. `RequireAssertion()` con lambda
12. `RequireUserName()`
13. Multiple requirements en una policy
14. `IAuthorizationRequirement`
15. `AuthorizationHandler<TRequirement>`
16. Custom requirement y handler
17. `HandleRequirementAsync`
18. `context.Succeed(requirement)`
19. `context.Fail()`
20. Resource-based authorization: `[Authorize]` con resource
21. `IAuthorizationService.AuthorizeAsync(user, resource, policy)`
22. `AuthorizationHandlerContext`
23. Multiple handlers para el mismo requirement
24. `OperationAuthorizationRequirement`
25. CRUD operations authorization
26. `IAuthorizationHandler` direct (sin generic)
27. Handler que inspecciona el recurso
28. Ejemplo: solo el dueño puede editar su perfil
29. Ejemplo: solo managers pueden aprobar pedidos > $1000
30. Authorization filters y resource authorization
31. `AuthorizeFilter` personalizado
32. Authorization en Razor Pages
33. `@attribute [Authorize]`
34. Authorization en View Components
35. `IAuthorizationService` en View Components
36. Authorization en Minimal APIs
37. `RequireAuthorization()` en route groups
38. Named authorization policies
39. Default policy: `options.DefaultPolicy`
40. Fallback policy: `options.FallbackPolicy`
41. `AllowAnonymous` y su interacción con policies
42. `AuthorizationMiddleware`
43. `[Authorize(Policy = "...")]` con `AuthenticationSchemes`
44. Multiple schemes y authorization
45. Claims: tipos comunes
46. Claims: custom claims
47. Claims transformation: `IClaimsTransformation`
48. Agregar claims después de autenticación
49. Claims y JWT
50. Claims y cookies
51. Claims-based vs role-based: cuándo usar cada uno
52. Feature-based authorization
53. Permission-based authorization
54. Permission claims y granularity
55. `RequireClaim("permission", "products.create")`
56. Hierarchical permissions
57. Permission store (database)
58. Dynamic authorization: load policies from database
59. `IAuthorizationPolicyProvider`
60. Custom policy provider
61. Named policies dinámicas
62. `AuthorizationOptions.AddPolicy` dinámico
63. Resource-based en API controllers
64. Resource-based en MVC controllers
65. `AuthorizationService` injection
66. Custom `AuthorizationFailureReason`
67. `IAuthorizationRequirement` con propiedades
68. Handler registration: `AddSingleton<IAuthorizationHandler, MyHandler>()`
69. Handler ordering
70. Multiple requirements: ALL must pass
71. Any requirement (OR logic)
72. Custom `IAuthorizationRequirementProcessor`
73. Authorization middleware pipeline order
74. `[Authorize]` vs `RequireAuthorization()`
75. `[AllowAnonymous]` en endpoints específicos
76. Authorization y areas
77. Authorization y multi-tenancy
78. Authorization testing
79. Mock `IAuthorizationService` en tests
80. Test authorization handlers
81. Integration testing con authorization
82. `TestAuthHandler` para bypass authorization en tests
83. Authorization y logging
84. Authorization y auditing
85. Failed authorization attempts logging
86. Authorization y GDPR
87. Authorization y OWASP
88. Horizontal privilege escalation prevention
89. Vertical privilege escalation prevention
90. CORS y authorization
91. Rate limiting y authorization
92. API key authorization
93. HMAC authorization
94. IP-based authorization
95. Time-based authorization (business hours only)
96. Location-based authorization
97. Device-based authorization
98. Authorization y microservicios
99. Policy server (centralized authorization)
100. Best practices de authorization en producción

---

## MÓDULO 26: CORS (CROSS-ORIGIN RESOURCE SHARING)

**Descripción:** Entenderás qué es CORS, por qué las aplicaciones web lo necesitan, cómo configurarlo correctamente en ASP.NET Core, y cómo evitar los errores de CORS más comunes que todo desarrollador web enfrenta.

1. Same-Origin Policy: qué es y por qué existe
2. Qué es un "origin" (protocol + host + port)
3. ¿Qué es CORS?
4. Preflight requests (OPTIONS)
5. Simple requests vs preflighted requests
6. CORS headers: `Access-Control-Allow-Origin`
7. `Access-Control-Allow-Methods`
8. `Access-Control-Allow-Headers`
9. `Access-Control-Expose-Headers`
10. `Access-Control-Allow-Credentials`
11. `Access-Control-Max-Age`
12. `AddCors()` en `Program.cs`
13. `UseCors()` en middleware pipeline
14. Named CORS policies: `AddCors(options => options.AddPolicy("AllowAll", ...))`
15. `AllowAnyOrigin()`, `AllowAnyMethod()`, `AllowAnyHeader()`
16. `WithOrigins("https://myapp.com")`
17. `WithMethods("GET", "POST")`
18. `WithHeaders("Authorization", "Content-Type")`
19. `AllowCredentials()` (no compatible con `AllowAnyOrigin`)
20. Multiple allowed origins
21. Dynamic origins: `SetIsOriginAllowed(origin => ...)`
22. `SetIsOriginAllowed(_ => true)` (equivalent to AllowAny)
23. Subdomain matching
24. CORS y credentials (cookies, auth headers)
25. `Access-Control-Allow-Credentials: true`
26. Why `AllowAnyOrigin()` + `AllowCredentials()` no funciona
27. `[EnableCors("policyName")]` attribute
28. `[DisableCors]` attribute
29. CORS en controllers
30. CORS en endpoints
31. CORS per endpoint con `.RequireCors()`
32. Different CORS policies per endpoint
33. CORS en Minimal APIs: `.RequireCors(policy)`
34. CORS middleware ordering (debe ir después de `UseRouting`)
35. `app.UseCors()` antes de `app.UseAuthorization()`
36. CORS y authentication
37. CORS preflight y authentication
38. `Authorization` header en preflight
39. Custom headers en preflight
40. `Content-Type: application/json` y preflight
41. Common CORS errors:
42. "No 'Access-Control-Allow-Origin' header"
43. "Response to preflight request doesn't pass access control check"
44. "The value of the 'Access-Control-Allow-Origin' header... cannot be '*'"
45. Debugging CORS en browser DevTools
46. Network tab y preflight requests
47. Console errors de CORS
48. CORS y reverse proxy (Nginx, IIS)
49. CORS en production con specific origins
50. CORS y development (localhost)
51. Multiple frontend apps con diferentes origins
52. CORS y CDN origins
53. CORS y SPA frameworks (Angular, React, Vue)
54. CORS y Blazor WebAssembly
55. CORS y file uploads
56. CORS y streaming
57. CORS y SignalR
58. CORS y WebSockets
59. CORS y Error responses
60. Error details en CORS response
61. CORS y security considerations
62. Don't use `AllowAnyOrigin()` in production
63. CORS is not a security mechanism (defense in depth)
64. CORS y CSRF
65. CORS y XSS
66. CORS y API security
67. CORS y rate limiting
68. CORS y caching
69. Vary: Origin header
70. CORS y content negotiation
71. CORS y response compression
72. CORS y output caching
73. CORS y response caching
74. CORS headers en error responses
75. Expose custom headers
76. `Access-Control-Expose-Headers: X-Custom-Header`
77. `X-Requested-With` header
78. CORS con API Gateway
79. CORS en YARP (reverse proxy)
80. CORS en Azure API Management
81. CORS en AWS API Gateway
82. CORS y microservices (multiple CORS configurations)
83. Testing CORS
84. Integration tests con CORS
85. Manual CORS testing con curl
86. `curl -H "Origin: ..." -X OPTIONS ...`
87. CORS testing tools
88. CORS y frontend development proxy
89. Proxy como alternativa a CORS
90. CORS y service workers
91. CORS y iframes
92. CORS y XMLHttpRequest
93. CORS y Fetch API
94. CORS y cookies con `credentials: 'include'`
95. CORS y `withCredentials: true` (axios)
96. CORS y environment-specific configuration
97. CORS y load balancer
98. CORS y health check endpoints
99. CORS y Swagger UI
100. Best practices de CORS en producción

---

## MÓDULO 27: API VERSIONING

**Descripción:** Aprenderás a versionar tu API para que puedas hacer cambios sin romper clientes existentes. Explorarás diferentes estrategias de versionado y cómo implementarlas con ASP.NET Core.

1. ¿Por qué versionar una API?
2. Breaking changes vs non-breaking changes
3. Versioning strategies overview
4. URL path versioning (`/v1/productos`, `/v2/productos`)
5. Query string versioning (`/api/productos?api-version=1.0`)
6. Header versioning (`X-API-Version: 1.0`)
7. Media type versioning (`Accept: application/vnd.myapi.v1+json`)
8. Pros y contras de cada estrategia
9. `Asp.Versioning.Mvc` NuGet package
10. `Asp.Versioning.Mvc.ApiExplorer`
11. `AddApiVersioning()` configuration
12. `AssumeDefaultVersionWhenUnspecified`
13. `DefaultApiVersion`
14. `ReportApiVersions` header
15. `ApiVersionReader` configuration
16. `UrlSegmentApiVersionReader`
17. `QueryStringApiVersionReader`
18. `HeaderApiVersionReader`
19. `MediaTypeApiVersionReader`
20. Multiple version readers
21. `[ApiVersion("1.0")]` attribute
22. `[ApiVersion("2.0")]` attribute
23. `[MapToApiVersion("1.0")]` en actions
24. `[MapToApiVersion("2.0")]` en actions
25. Controller versioning
26. Same controller para múltiples versiones
27. Different controllers por versión
28. Controller naming: `ProductosV1Controller`, `ProductosV2Controller`
29. Version-neutral endpoints
30. `[ApiVersionNeutral]`
31. Deprecated versions: `Deprecated = true`
32. Sunset versions
33. Version en route: `v{version:apiVersion}`
34. Route template con version
35. `IApiVersioningBuilder`
36. `AddMvc()` con versioning
37. `AddApiExplorer()` para Swagger
38. Swagger con múltiples versiones
39. `SwaggerDoc` por versión
40. Swagger UI dropdown por versión
41. `GroupApiVersions` strategy
42. Model versioning (different DTOs por versión)
43. V1: `ProductoV1Dto`, V2: `ProductoV2Dto`
44. Mapping entre versiones
45. AutoMapper profiles por versión
46. Service layer con versioning
47. Shared services entre versiones
48. Version-specific services
49. Version negotiation
50. Content negotiation con versioning
51. Accept header versioning + JSON media types
52. `application/vnd.myapi.v1+json`
53. Custom `ApiVersionReader`
54. Conventions-based versioning
55. `options.Conventions.Controller<T>().HasApiVersion(1.0)`
56. Versioning y dependency injection
57. Register services per version
58. Versioning y testing
59. Integration tests per version
60. Version deprecation strategy
61. Communication plan para deprecation
62. `Deprecation` header
63. `Sunset` header (RFC 8594)
64. Versioning y API Gateway
65. Version routing en YARP
66. Versioning y backward compatibility
67. Versioning y breaking changes policy
68. Versioning y client SDKs
69. Auto-generated client per version
70. Versioning y documentation
71. Changelog per version
72. Migration guides entre versiones
73. Versioning y microservices
74. Versioning y semantic versioning (SemVer)
75. Major vs minor version changes
76. Beta/preview versions
77. Version negotiation en clients
78. Version discovery
79. API version metadata
80. `IApiVersionMetadata`
81. Versioning y error responses
82. Versioning y rate limiting (per version)
83. Versioning y caching (per version)
84. Versioning y CORS
85. Versioning y authorization
86. Versioning y middleware
87. Versioning y health checks
88. Minimal APIs versioning
89. `AddApiVersioning().AddApiExplorer()`
90. `.HasApiVersion(1.0)` en minimal APIs
91. Versioning y output caching
92. Versioning y response caching
93. Multi-version maintenance burden
94. When not to version (internal APIs)
95. Contract-first versioning
96. Versioning strategies comparison matrix
97. Real-world versioning examples (GitHub, Stripe, Twilio)
98. Stripe API versioning model
99. GitHub API versioning model
100. Best practices de API versioning

---

## MÓDULO 28: RAZOR PAGES

**Descripción:** Aprenderás Razor Pages, el modelo de programación page-based de ASP.NET Core que simplifica el desarrollo de escenarios basados en páginas. Es ideal para aplicaciones donde cada página tiene su propia lógica y no necesitas la complejidad de MVC.

1. ¿Qué son Razor Pages?
2. Razor Pages vs MVC: diferencias fundamentales
3. ¿Cuándo usar Razor Pages vs MVC?
4. Page-based vs controller-based
5. Crear proyecto Razor Pages: `dotnet new webapp`
6. Estructura del proyecto
7. `/Pages` folder convention
8. `Index.cshtml` y `Index.cshtml.cs` (code-behind)
9. `PageModel`: la clase de lógica
10. `OnGet()` handler
11. `OnPost()` handler
12. `OnGetAsync()` y `OnPostAsync()`
13. `IActionResult` como return type
14. `Page()` result
15. `RedirectToPage()` result
16. `RedirectToPage("./Index")`
17. `RedirectToPage("/Productos/Details", new { id = 1 })`
18. `Page()` para mostrar la página
19. `NotFound()` en PageModel
20. `BadRequest()` en PageModel
21. `Content()` para texto simple
22. `File()` para archivos
23. `@page` directive
24. `@page "{id:int}"` - route parameters en pages
25. `@page "{id:int?}"` - optional parameters
26. `@page "{*slug}"` - catch-all parameters
27. Custom routes per page
28. `@model` directive en pages
29. `[BindProperty]` attribute
30. `[BindProperty(SupportsGet = true)]`
31. `[BindProperty(Name = "q")]`
32. Multiple properties binding
33. `TempData` en Razor Pages
34. `ViewData` y `ViewBag` en Razor Pages
35. Page handlers: `OnGet`, `OnPost`, `OnPut`, `OnDelete`
36. Named handlers: `OnPostDelete()`
37. `asp-page-handler` Tag Helper
38. Multiple forms en una página
39. Named handler routing: `/Page?handler=Delete`
40. Handler parameters
41. AJAX handlers en Razor Pages
42. Return `PartialView()` desde handlers
43. Return `Json()` desde handlers
44. `[ValidateAntiForgeryToken]` en POST
45. Anti-forgery automático en Razor Pages
46. `[IgnoreAntiforgeryToken]`
47. Layouts en Razor Pages
48. `_ViewImports.cshtml` en Pages
49. `_ViewStart.cshtml` en Pages
50. Sections en Razor Pages
51. Partial views en Razor Pages
52. `_Pages/Shared/_ProductCard.cshtml`
53. View Components en Razor Pages
54. Dependency injection en PageModel
55. Constructor injection
56. `[FromServices]` attribute
57. Model validation en Razor Pages
58. `ModelState.IsValid`
59. Validation summary en Razor Pages
60. `asp-validation-for` en Razor Pages
61. Remote validation en Razor Pages
62. `IActionContextAccessor` en Razor Pages
63. `IUrlHelper` en Razor Pages
64. URL generation: `Url.Page("/Products/Details", new { id = 1 })`
65. Areas con Razor Pages
66. `/Areas/Admin/Pages/`
67. `@page "/admin/products"`
68. Razor Pages y filter attributes
69. `[Authorize]` en Razor Pages
70. Page filters: `IPageFilter`
71. `IAsyncPageFilter`
72. `PageHandlerExecutingContext`
73. `PageHandlerExecutedContext`
74. Global page filters
75. Scaffolding Razor Pages
76. CRUD con Razor Pages
77. List page con Razor Pages
78. Details page
79. Create page (GET y POST)
80. Edit page (GET y POST)
81. Delete page (GET y POST)
82. Delete con confirmation modal
83. Razor Pages con Entity Framework Core
84. `DbContext` injection en PageModel
85. Pagination en Razor Pages
86. Sorting en Razor Pages
87. Searching en Razor Pages
88. File upload en Razor Pages
89. Multiple file upload
90. Razor Pages con API calls (backend API)
91. Razor Pages SPA-like (JavaScript integration)
92. Razor Pages performance
93. Compiled Razor Pages
94. Runtime compilation en development
95. Testing Razor Pages
96. `PageModel` testing
97. Integration testing de pages
98. Razor Pages y multi-tenancy
99. Razor Pages y localization
100. Best practices de Razor Pages

---

## MÓDULO 29: SIGNALR – APLICACIONES EN TIEMPO REAL

**Descripción:** Aprenderás a usar SignalR para agregar funcionalidad en tiempo real a tus aplicaciones ASP.NET Core. Chat, notificaciones push, dashboards en vivo, y cualquier escenario donde el servidor necesita comunicarse con los clientes sin que estos lo soliciten.

1. ¿Qué es SignalR?
2. ¿Qué son las aplicaciones en tiempo real?
3. SignalR: transportes (WebSockets, Server-Sent Events, Long Polling)
4. SignalR: negocia el transporte automáticamente
5. Hubs: concepto y creación
6. `Hub` class
7. `Hub<T>` para strongly-typed hubs
8. Hub methods: métodos que el cliente invoca
9. `Clients` property: acceso a clientes conectados
10. `Clients.All.SendAsync("method", data)` - broadcast a todos
11. `Clients.Caller.SendAsync(...)` - solo al llamador
12. `Clients.Others.SendAsync(...)` - a todos excepto el llamador
13. `Clients.Client(connectionId).SendAsync(...)` - a uno específico
14. `Clients.Group("groupName").SendAsync(...)` - a un grupo
15. `Groups.AddToGroupAsync(connectionId, groupName)`
16. `Groups.RemoveFromGroupAsync(connectionId, groupName)`
17. `Clients.OthersInGroup("groupName").SendAsync(...)`
18. `Clients.Clients(connectionIds).SendAsync(...)` - múltiples
19. Hub lifecycle: `OnConnectedAsync()`, `OnDisconnectedAsync()`
20. `Context.ConnectionId`
21. `Context.User`
22. `Context.UserIdentifier`
23. Register SignalR: `AddSignalR()`
24. Map hub: `app.MapHub<ChatHub>("/chat")`
25. Hub endpoint routing
26. Strongly-typed hub: `Hub<IMyHub>`
27. Interface para hub: `Task SendMessage(string user, string message)`
28. Hub method invocation con DTOs
29. Hub method invocation con parámetros complejos
30. Return values desde hub methods
31. Streaming hub methods: `IAsyncEnumerable<T>`
32. Client-to-server streaming
33. Server-to-client streaming
34. JavaScript client: `@microsoft/signalr` npm package
35. `HubConnectionBuilder` en JavaScript
36. `.withUrl("/chat")`
37. `.configureLogging()`
38. `.build()`
39. `.start()` - iniciar conexión
40. `.invoke("Method", args)` - invocar hub method
41. `.on("MethodName", callback)` - escuchar eventos del servidor
42. `.onclose(callback)` - reconexión
43. Automatic reconnect: `.withAutomaticReconnect()`
44. Reconnect events: `onreconnecting`, `onreconnected`
45. Manual reconnect
46. Connection state management
47. SignalR con authentication
48. `[Authorize]` en hub class
49. `[Authorize]` en hub methods
50. JWT authentication con SignalR
51. Access token en query string o header
52. `AccessTokenProvider` en JS client
53. User ID provider: `IUserIdProvider`
54. `DefaultUserIdProvider` (uses NameIdentifier claim)
55. Custom `IUserIdProvider`
56. `Clients.User(userId)` - enviar a un usuario específico
57. SignalR groups: chat rooms
58. Multi-room chat implementation
59. Private messaging con SignalR
60. Notificaciones push con SignalR
61. Dashboard en vivo con SignalR
62. Real-time data updates
63. SignalR con Blazor
64. `HubConnection` en Blazor
65. SignalR en Razor Pages con JavaScript
66. SignalR en MVC con JavaScript
67. SignalR con Vue.js
68. SignalR con React
69. SignalR con Angular
70. SignalR con TypeScript
71. Backplane: Redis para escalar SignalR
72. `AddStackExchangeRedis()` backplane
73. Azure SignalR Service
74. `AddAzureSignalR()`
75. SignalR sin sticky sessions (Redis o Azure)
76. SignalR y load balancing
77. SignalR y reverse proxy
78. SignalR con Nginx
79. SignalR con IIS
80. SignalR con Azure App Service
81. SignalR con Docker
82. SignalR protocol: JSON vs MessagePack
83. `AddNewtonsoftJsonProtocol()` o `AddJsonProtocol()`
84. MessagePack serialization
85. Custom serialization
86. SignalR y logging
87. SignalR y error handling
88. Hub exceptions y clients
89. Hub filters
90. `IHubFilter` y `IHubLifetimeManager`
91. Rate limiting en hub methods
92. Hub method performance
93. Scaling SignalR: considerations
94. Memory management con SignalR (connection tracking)
95. Connection management: tracking users
96. Online users feature
97. Typing indicators
98. Read receipts
99. SignalR y integration testing
100. Best practices de SignalR en producción

---

## MÓDULO 30: BLAZOR SERVER

**Descripción:** Aprenderás Blazor Server, que te permite construir interfaces web interactivas usando C# en lugar de JavaScript. El componente se ejecuta en el servidor y la UI se actualiza en tiempo real vía SignalR.

1. ¿Qué es Blazor?
2. Blazor Server vs Blazor WebAssembly vs Blazor United (.NET 8)
3. Component model en Blazor
4. `.razor` files
5. Component syntax: HTML + C# + Razor
6. `@page` directive para routing
7. `@code` block
8. Component parameters: `[Parameter]`
9. `RenderFragment` (child content)
10. `RenderFragment<T>` (templated components)
11. Data binding: `@bind` directive
12. `@bind-value` y `@bind-value:event`
13. Event handling: `@onclick`, `@onchange`
14. `EventCallback<T>`
15. `EventCallback.Factory.Create`
16. Component lifecycle: `OnInitialized`, `OnParametersSet`
17. `OnInitializedAsync`, `OnParametersSetAsync`
18. `OnAfterRender`, `OnAfterRenderAsync`
19. `ShouldRender()` override
20. `StateHasChanged()` para forzar re-render
21. Cascading values y parameters: `[CascadingParameter]`
22. `<CascadingValue>`
23. Dependency injection en Blazor components
24. `@inject` directive
25. `[Inject]` attribute
26. Scoped services en Blazor Server (per circuit, no per request)
27. Singleton y transient services en Blazor Server
28. Navigation: `NavigationManager`
29. `NavigateTo()` y force load
30. Routing en Blazor: `<Router>` component
31. Route parameters
32. Optional route parameters
33. Catch-all route parameters
34. `@attribute [Authorize]`
35. `<AuthorizeView>` component
36. `<Authorized>`, `<NotAuthorized>`, `<Authorizing>`
37. `AuthenticationState` y `AuthenticationStateProvider`
38. Cascading authentication state
39. Blazor Server forms: `<EditForm>`
40. `EditContext`
41. `DataAnnotationsValidator`
42. `<ValidationSummary>`
43. `<ValidationMessage>`
44. `InputText`, `InputNumber`, `InputSelect`, `InputCheckbox`
45. `InputDate`, `InputTextArea`
46. `InputRadioGroup` e `InputRadio`
47. Custom form components
48. Form submission: `OnValidSubmit`, `OnInvalidSubmit`
49. `IValidatableObject` en Blazor
50. JS interop: `IJSRuntime`
51. `InvokeAsync<T>()` para llamar JavaScript
52. `[JSInvokable]` attribute
53. `DotNetObjectReference` para callbacks desde JS
54. Isolation CSS en Blazor: `::after` scoped CSS
55. `ComponentBase` class
56. `OwningComponentBase<T>` para scoped services
57. Shared state patterns en Blazor Server
58. State containers (scoped services para state)
59. SignalR hub desde Blazor Server
60. Blazor Server y reconnection
61. `ReconnectionHandler`
62. Disconnected UI handling
63. Blazor Server: circuit management
64. Circuit limits
65. `MaxBufferedUnacknowledgedRenderBatches`
66. Blazor Server performance
67. Prerendering en Blazor Server
68. `RenderMode.InteractiveServer` (.NET 8)
69. `.NET 8` component render modes
70. Static SSR, Interactive Server, Interactive WebAssembly, Auto
71. `<HeadContent>` y `<PageTitle>`
72. `<ErrorBoundary>` component
73. Component libraries: Razor Class Libraries
74. MudBlazor / Radzen como component libraries
75. Componentes reutilizables en Blazor
76. Generic components: `<MyComponent TItem="Product" />`
77. Templated components con RenderFragment
78. Virtualize component (virtual scrolling)
79. `InputFile` para file upload
80. Blazor y Entity Framework Core
81. Blazor y HttpClient
82. Blazor y authentication (cookies, JWT)
83. Blazor Server y IIS deployment
84. Blazor Server y Nginx deployment
85. Blazor Server y Azure deployment
86. Blazor Server y Docker
87. SignalR circuit debugging
88. Blazor Server unit testing con bUnit
89. Blazor Server integration testing
90. Component testing con bUnit
91. Mocking services en bUnit
92. Event callback testing
93. Form testing con bUnit
94. Blazor Server y localization
95. Blazor Server y global error handling
96. Blazor Server y logging
97. Blazor Server y output caching
98. Blazor Server vs Blazor WebAssembly comparison
99. Blazor Server scalability considerations
100. Best practices de Blazor Server

---

## MÓDULO 31: BLAZOR WEBASSEMBLY (WASM)

**Descripción:** Aprenderás Blazor WebAssembly, que ejecuta tu aplicación .NET directamente en el navegador del cliente usando WebAssembly. No hay dependencia de la conexión al servidor para la interactividad de la UI (a diferencia de Blazor Server).

1. ¿Qué es WebAssembly (Wasm)?
2. Blazor WASM: cómo funciona (descarga .NET runtime al navegador)
3. Blazor Server vs Blazor WASM: diferencias técnicas
4. Crear proyecto Blazor WASM: `dotnet new blazorwasm`
5. Estructura del proyecto
6. `wwwroot/index.html`
7. `Program.cs` en Blazor WASM
8. `WebAssemblyHostBuilder`
9. `_Imports.razor` global usings
10. `App.razor` y `<Router>`
11. Component model (igual que Blazor Server)
12. Dependency injection en Blazor WASM
13. `builder.Services`
14. HttpClient en Blazor WASM (`builder.Services.AddScoped(sp => new HttpClient { BaseAddress = ... })`)
15. Call API from Blazor WASM
16. Authentication en Blazor WASM
17. `Microsoft.AspNetCore.Components.WebAssembly.Authentication`
18. OIDC authentication
19. `AddOidcAuthentication()`
20. `<AuthorizeView>`, `<AuthorizeRouteView>`
21. `AuthenticationService` en WASM
22. Token-based auth con API
23. `BaseAddressAuthorizationMessageHandler`
24. `IAccessTokenProvider`
25. JWT token management
26. Blazor WASM PWA (Progressive Web App)
27. Service worker en Blazor WASM
28. Offline support
29. Install as app
30. Blazor WASM AOT compilation
31. Trimming y publish size
32. `BlazorEnableAOT`
33. Lazy loading de assemblies
34. `LazyAssemblyLoader`
35. Blazor WASM performance
36. Reducing download size
37. Caching strategies
38. IL trimming
39. Linker configuration (`LinkerConfig.xml`)
40. Prerendering en Blazor WASM
41. `RenderMode.InteractiveWebAssembly` (.NET 8)
42. Hosted Blazor WASM (con ASP.NET Core backend)
43. `dotnet new blazorwasm --hosted`
44. Client, Server, Shared projects
45. Shared models entre client y server
46. API en el proyecto Server
47. Blazor WASM standalone vs hosted
48. SignalR desde Blazor WASM
49. Real-time updates en WASM
50. JavaScript interop en WASM
51. `IJSRuntime` en WASM
52. File handling en WASM
53. `InputFile` component
54. Upload file to API desde WASM
55. Download files en WASM
56. LocalStorage y SessionStorage
57. `ProtectedLocalStorage` y `ProtectedSessionStorage`
58. IndexedDB interop
59. Cookies desde WASM
60. Error handling en Blazor WASM
61. Global error boundary
62. Unhandled exceptions
63. Network error handling
64. Offline detection
65. Blazor WASM con .NET 8 (unified model)
66. Interactive WebAssembly render mode
67. Auto render mode (start Server, switch to WASM)
68. Component-level render mode selection
69. Per-page render mode
70. Per-component render mode
71. Blazor United (.NET 8) concept
72. SSR + WebAssembly interactivity
73. Streaming rendering
74. Enhanced form handling (.NET 8)
75. Blazor WASM deployment: static files
76. Deploy a Azure Static Web Apps
77. Deploy a Azure Storage
78. Deploy con Nginx
79. Deploy con IIS
80. Deploy con GitHub Pages
81. Docker para hosted Blazor WASM
82. CI/CD para Blazor WASM
83. Testing Blazor WASM components
84. bUnit con Blazor WASM
85. E2E testing con Playwright
86. E2E testing con Selenium
87. Debugging Blazor WASM en browser
88. DevTools para Blazor WASM
89. Network debugging
90. Performance profiling
91. Blazor WASM y SEO (challenges)
92. Blazor WASM y SSR para SEO
93. Blazor WASM y accessibility
94. Blazor WASM y globalization
95. Blazor WASM con第三方 component libraries
96. MudBlazor en WASM
97. Radzen en WASM
98. Telerik para Blazor
99. Syncfusion para Blazor
100. Best practices de Blazor WASM en producción

---

## MÓDULO 32: BLAZOR UNITED (.NET 8) Y NUEVOS PARADIGMAS

**Descripción:** Con .NET 8, Blazor se unifica en un único modelo de programación que permite combinar Server-Side Rendering, Server interactivity, WebAssembly, y Auto mode. Aprenderás este nuevo paradigma que es el futuro de Blazor.

1. Blazor United: concepto y filosofía
2. `dotnet new blazor` (.NET 8)
3. Render modes en .NET 8
4. `RenderMode.Static` (SSR puro, sin interactividad)
5. `RenderMode.InteractiveServer` (Blazor Server)
6. `RenderMode.InteractiveWebAssembly` (Blazor WASM)
7. `RenderMode.Auto` (inicia Server, luego WASM)
8. `@rendermode` directive per component
9. `@rendermode InteractiveServer`
10. `@rendermode InteractiveWebAssembly`
11. `@rendermode Auto`
12. Per-page render mode
13. Per-component render mode
14. Global render mode en `App.razor`
15. `<HeadOutlet>` component
16. `<Routes>` component
17. `InteractiveServerRenderMode`, `InteractiveWebAssemblyRenderMode`
18. SSR: Server-Side Rendering
19. SSR con enhanced navigation
20. SSR con enhanced forms
21. Form handling en SSR mode
22. `FormName` attribute
23. `OnPost` handler en SSR
24. SSR sin interactividad (pure HTML rendering)
25. Streaming SSR
26. `<StreamedContent>` (.NET 8 concept)
27. `OnInitializedAsync` y streaming
28. Progressive rendering
29. `@attribute [StreamRendering]`
30. `@attribute [StreamRendering(true)]`
31. Enhanced navigation (SPA-like navigation en SSR)
32. `data-enhance-nav`
33. Enhanced form handling
34. `data-enhance`
35. Antiforgery tokens en SSR forms
36. Model binding en SSR forms
37. Validation en SSR forms
38. PRG pattern en SSR
39. Auto render mode: how it works
40. Auto: start with Server, switch to WASM
41. Blazor Web App template (.NET 8)
42. `Components` folder structure
43. `Components/Layout`
44. `Components/Pages`
45. `Components/_Imports.razor`
46. `Components/App.razor`
47. Client-side services para WASM components
48. Server-side services para Server components
49. Shared services
50. Persistent state entre render modes
51. Component state across render modes
52. JavaScript interop differences por render mode
53. DI differences por render mode
54. Authentication en unified Blazor
55. `CascadingAuthenticationState` en .NET 8
56. `AuthorizeView` en unified model
57. Identity en Blazor Web App
58. Individual Accounts template
59. ASP.NET Core Identity con Blazor
60. Identity UI components
61. Login, Register, Manage pages
62. External login providers en Blazor
63. Two-factor auth en Blazor
64. Identity API endpoints
65. Identity y SSR forms
66. Blazor y Minimal APIs
67. Blazor y SignalR
68. Blazor y gRPC-Web
69. Blazor y GraphQL
70. Component libraries para .NET 8 Blazor
71. MudBlazor 6+ con .NET 8
72. Telerik UI para Blazor .NET 8
73. Radzen Blazor .NET 8
74. QuickGrid component (.NET 8)
75. `<QuickGrid>` para tablas
76. QuickGrid con EF Core
77. QuickGrid pagination, sorting
78. Blazor .NET 8 y static assets
79. `MapStaticAssets()` en .NET 8
80. Blazor .NET 8 y output caching
81. Blazor .NET 8 y response caching
82. Blazor .NET 8 y health checks
83. Blazor .NET 8 y diagnostics
84. Blazor .NET 8 deployment
85. Deploy Blazor Web App con IIS
86. Deploy con Nginx
87. Deploy con Azure App Service
88. Deploy con Docker
89. CI/CD pipeline para Blazor Web App
90. Blazor .NET 9 preview features
91. Blazor y AI integration (.NET 9)
92. Blazor Hybrid (MAUI Blazor)
93. MAUI Blazor concepto
94. MAUI Blazor project template
95. Share components entre web y desktop/mobile
96. Blazor Hybrid con WPF
97. Blazor Hybrid con WinForms
98. Electron.NET con Blazor
99. Blazor y .NET Aspire
100. Future of Blazor: roadmap

---

## MÓDULO 33: MINIMAL APIs

**Descripción:** Aprenderás Minimal APIs, la forma simplificada de construir APIs en ASP.NET Core sin la ceremonia de controllers. Ideal para microservicios, APIs pequeñas, y cuando quieres construir endpoints rápidamente.

1. ¿Qué son Minimal APIs?
2. Minimal APIs vs API Controllers
3. `WebApplication.CreateBuilder(args)`
4. `builder.Build()`
5. `app.MapGet("/", () => "Hello")`
6. `app.MapPost`, `app.MapPut`, `app.MapDelete`, `app.MapPatch`
7. `app.Run()`
8. Route parameters: `app.MapGet("/products/{id}", (int id) => ...)`
9. Query parameters: `app.MapGet("/search", (string q) => ...)`
10. Header parameters: `[FromHeader]`
11. Body parameters: `[FromBody]`
12. Multiple parameter binding
13. Complex types from body (automatic `[FromBody]`)
14. Multiple complex types (no permitido, usar tupla o wrapper)
15. `IResult` return type
16. `Results.Ok()`, `Results.NotFound()`, `Results.BadRequest()`
17. `Results.Created()`, `Results.NoContent()`
18. `Results.Unauthorized()`, `Results.Forbid()`
19. `Results.Conflict()`, `Results.UnprocessableEntity()`
20. `Results.Json()`, `Results.Text()`
21. `Results.File()`, `Results.Stream()`
22. `Results.Redirect()`
23. `Results.Problem()`
24. `Results.Extensions`
25. Typed results: `Ok<T>`, `NotFound`, `Created<T>`
26. `IResult` interface
27. Delegate-based handlers (lambda)
28. Method group handlers
29. `app.MapGet("/products", GetProducts)`
30. Route groups: `app.MapGroup("/api/v1")`
31. Nested groups
32. Group-level authorization: `.RequireAuthorization()`
33. Group-level CORS: `.RequireCors()`
34. Group-level rate limiting: `.RequireRateLimiting()`
35. Endpoint filters
36. `AddEndpointFilter<MyFilter>()`
37. `IEndpointFilter` y `EndpointFilterInvocationContext`
38. Endpoint filter: validation
39. Endpoint filter: logging
40. Endpoint filter: response modification
41. Endpoint metadata: `.WithName()`, `.WithTags()`
42. `.WithOpenApi()` para Swagger
43. `.WithDescription()`, `.WithSummary()`
44. `.Produces<T>()`, `.ProducesProblem()`
45. `.Accepts<T>()`
46. `.DisableAntiforgery()`
47. Dependency injection en handlers
48. Constructor injection (en classes con handlers)
49. Parameters from DI (automatic `[FromServices]`)
50. `HttpContext` as parameter
51. `HttpRequest` y `HttpResponse` as parameters
52. `CancellationToken` as parameter
53. `ClaimsPrincipal` as parameter
54. `ILogger` as parameter
55. `LinkGenerator` for URL generation
56. Minimal API y authentication
57. `.RequireAuthorization("policy")`
58. `[Authorize]` en handler methods
59. Minimal API y CORS
60. Minimal API y rate limiting
61. Minimal API y output caching
62. Minimal API y response caching
63. Minimal API y response compression
64. Minimal API y health checks
65. Minimal API y exception handling
66. `app.UseExceptionHandler()`
67. ProblemDetails con Minimal APIs
68. Minimal API y validation
69. FluentValidation con Minimal APIs
70. Manual validation en handlers
71. Minimal API con EF Core
72. CRUD endpoints con Minimal APIs
73. Paginated responses
74. Search endpoints
75. File upload en Minimal APIs
76. File download
77. Streaming responses
78. SignalR y Minimal APIs (coexistencia)
79. Minimal API y testing
80. `WebApplicationFactory` para tests
81. Testing individual endpoints
82. Integration testing con Minimal APIs
83. Unit testing handlers
84. Minimal API y middleware
85. Custom middleware en Minimal API apps
86. Minimal API y logging
87. Minimal API y configuration
88. Minimal API y Options Pattern
89. Minimal API en microservices
90. Minimal API con Docker
91. Minimal API deployment
92. Minimal API y API Gateway
93. Minimal API y YARP
94. Native AOT con Minimal APIs
95. Minimal API performance
96. Benchmarks: Minimal API vs Controllers
97. When to use Minimal APIs vs Controllers
98. Migrating from Controllers a Minimal APIs
99. Large applications con Minimal APIs (organización)
100. Best practices de Minimal APIs

---

## MÓDULO 34: CACHING (IN-MEMORY Y DISTRIBUIDO)

**Descripción:** Aprenderás a implementar caching en ASP.NET Core para mejorar drásticamente el rendimiento. Cubriremos caching en memoria, caching distribuido con Redis, response caching, output caching, y patrones avanzados de caching.

1. ¿Qué es caching y por qué es importante?
2. Cache hit vs cache miss
3. In-memory caching: `IMemoryCache`
4. `AddMemoryCache()` y `UseMemoryCache()`
5. `cache.Get<T>(key)`
6. `cache.Set<T>(key, value, options)`
7. `cache.GetOrCreate<T>(key, factory)`
8. `cache.GetOrCreateAsync<T>(key, factory)`
9. `MemoryCacheEntryOptions`
10. Absolute expiration (`AbsoluteExpirationRelativeToNow`)
11. Sliding expiration (`SlidingExpiration`)
12. Cache priority (`CacheItemPriority`)
13. Size limits
14. `cache.TryGetValue()` para verificar existencia
15. `cache.Remove(key)`
16. Cache compaction
17. `PostEvictionCallbacks`
18. Cache dependencies
19. Distributed caching: `IDistributedCache`
20. Distributed cache providers: Redis, SQL Server, NCache
21. `AddStackExchangeRedisCache()` para Redis
22. `AddDistributedSqlServerCache()` para SQL Server
23. `cache.GetString(key)`, `cache.SetString(key, value)`
24. `cache.GetAsync<T>()`, `cache.SetAsync<T>()` (extension methods)
25. `DistributedCacheEntryOptions`
26. Absolute y sliding expiration en distributed cache
27. Redis: instalación y configuración
28. Redis: data types (string, hash, list, set, sorted set)
29. Redis: pub/sub para cache invalidation
30. Redis: connection multiplexer
31. `ConnectionMultiplexer` en DI
32. `IDatabase` para operaciones directas de Redis
33. StackExchange.Redis NuGet package
34. Redis Sentinel y clustering
35. Redis como SignalR backplane
36. Redis como session store
37. Response caching: `app.UseResponseCaching()`
38. `[ResponseCache]` attribute
39. `ResponseCacheAttribute`: Duration, VaryByQueryKeys
40. `Cache-Control` headers
41. `Vary` header
42. Response caching y authentication (no cacheable)
43. Response caching middleware internals
44. `IResponseCachingFeature`
45. Custom response caching
46. Output caching (.NET 7): `app.UseOutputCache()`
47. Output caching vs response caching
48. `[OutputCache]` attribute
49. `OutputCacheOptions` y policies
50. `builder.Services.AddOutputCache()`
51. Named output cache policies
52. `AddPolicy("name", builder => ...)`
53. VaryByQueryKeys en output cache
54. VaryByRouteValues
55. VaryByHeader
56. VaryByValue (custom)
57. Cache revalidation (ETag, Last-Modified)
58. Output cache expiration
59. Output cache tag en Razor: `<cache>`
60. Distributed cache tag: `<distributed-cache>`
61. Cache-aside pattern
62. Write-through pattern
63. Write-behind (write-back) pattern
64. Read-through pattern
65. Cache warming
66. Cache stampede (thundering herd)
67. Cache penetration
68. Cache breakdown
69. Cache avalanche
70. Cache key design
71. Cache key naming conventions
72. Cache serialization formats
73. JSON serialization para cache
74. MessagePack serialization para cache
75. Cache versioning
76. Cache invalidation strategies
77. Time-based expiration
78. Event-based invalidation
79. Manual invalidation
80. Cache-aside con Entity Framework
81. Cache query results
82. Cache aggregates
83. Cache API responses
84. Cache external API calls
85. Cache computed values
86. Cache and data consistency
87. Cache en microservices
88. Distributed cache en microservices
89. Cache y multi-tenancy (tenant-specific keys)
90. Cache monitoring
91. Cache metrics (hit ratio, miss ratio)
92. Cache memory usage monitoring
93. Redis monitoring con RedisInsight
94. Cache performance testing
95. Cache benchmarks
96. Lazy loading + cache
97. Cache wrappers y abstractions
98. Hybrid caching (in-memory + distributed)
99. Two-level cache pattern
100. Best practices de caching en producción

---

## MÓDULO 35: BACKGROUND SERVICES (HOSTED SERVICES)

**Descripción:** Aprenderás a ejecutar tareas en segundo plano con ASP.NET Core. Desde `IHostedService` hasta `BackgroundService`, colas de trabajo, y cómo implementar procesamiento asíncrono de tareas largas sin bloquear las solicitudes HTTP.

1. ¿Qué son los Background Services?
2. `IHostedService` interface
3. `StartAsync(CancellationToken)` y `StopAsync(CancellationToken)`
4. `BackgroundService` base class
5. `ExecuteAsync(CancellationToken)`
6. `Task.Delay` loops en background services
7. Singleton lifetime de hosted services
8. DI en hosted services (cuidado con Scoped services)
9. `IServiceScopeFactory` para crear scopes
10. Long-running task en background service
11. Scheduled tasks con `PeriodicTimer` (.NET 6)
12. Timer-based background service
13. Cron-based scheduling
14. `Cronos` library para cron expressions
15. Quartz.NET para scheduling avanzado
16. Hangfire como alternativa a Quartz.NET
17. Hangfire: setup y configuración
18. Hangfire: `BackgroundJob.Enqueue()`
19. Hangfire: `BackgroundJob.Schedule()`
20. Hangfire: recurring jobs
21. Hangfire dashboard
22. Hangfire con SQL Server storage
23. Queue pattern: `Channel<T>`
24. `Channel.CreateBounded` y `CreateUnbounded`
25. Producer-consumer pattern
26. Background service como consumer
27. API controller como producer
28. `IBackgroundTaskQueue` interface
29. `BackgroundTaskQueue` implementation
30. `QueueBackgroundWorkItem()`
31. `DequeueAsync()` en background service
32. Multiple consumers
33. Parallel processing
34. `SemaphoreSlim` para control de concurrencia
35. Priority queue implementation
36. Delayed task execution
37. Fire-and-forget pattern (con cuidado)
38. `Task.Run()` en background (anti-pattern con DI)
39. Proper way: use queues or hosted services
40. `IHostApplicationLifetime` events
41. `ApplicationStarted`
42. `ApplicationStopping`
43. `ApplicationStopped`
44. Graceful shutdown
45. `CancellationToken` propagation
46. `IHostLifetime`
47. `ConsoleLifetime`
48. Multiple hosted services en la misma app
49. Ordering de hosted services
50. Background service que necesita datos de startup
51. Initialize on startup pattern
52. Database seed en background service
53. Cache warming en background service
54. Email sending en background service
55. File processing en background service
56. Image processing en background service
57. Report generation en background service
58. Data import/export en background service
59. Webhook delivery service
60. Health check publisher como hosted service
61. Metrics collection como hosted service
62. Log cleanup como hosted service
63. Background service y Entity Framework Core
64. DbContext scoped en background service
65. `CreateScope()` en background service
66. Background service y distributed cache
67. Background service y SignalR (enviar updates)
68. Background service y email (SMTP, SendGrid)
69. Background service y external API calls
70. Error handling en background services
71. Retry logic con Polly en background services
72. Logging en background services
73. Monitoring background services
74. Background service health checks
75. Custom health check para background service
76. Background services en Docker
77. Background services en Kubernetes
78. Background services en Azure App Service
79. Background services en Windows Service
80. `Microsoft.Extensions.Hosting.WindowsServices`
81. `UseWindowsService()`
82. Linux systemd service
83. `UseSystemd()`
84. Background services y graceful shutdown en containers
85. `SIGTERM` handling
86. `IHostedService` vs `BackgroundService`
87. `BackgroundService` stopping behavior
88. `ExecuteAsync` no awaited (bug common)
89. `stoppingToken` usage
90. Testing background services
91. Unit testing background services
92. Integration testing background services
93. `TimeProvider` para testable timers (.NET 8)
94. Mock timer en tests
95. Background services y configuration
96. Dynamic configuration para schedules
97. Enable/disable background services por environment
98. Background services y multi-tenancy
99. Background services patterns en microservices
100. Best practices de background services

---

## MÓDULO 36: FILE UPLOAD Y DOWNLOAD

**Descripción:** Aprenderás a manejar archivos en ASP.NET Core: desde uploads simples hasta uploads de archivos grandes con streaming, descargas, y almacenamiento en diferentes destinos (disco, base de datos, Azure Blob Storage).

1. File upload con `IFormFile`
2. `IFormFile` properties: `FileName`, `Length`, `ContentType`
3. `OpenReadStream()` para leer el archivo
4. `CopyToAsync(stream)` para guardar
5. Multipart form data
6. `enctype="multipart/form-data"` en formularios
7. `<input type="file" asp-for="Archivo" />`
8. Model binding con `IFormFile`
9. `IFormFileCollection` para múltiples archivos
10. Multiple `<input type="file" />`
11. Single input, multiple files: `multiple` attribute
12. File size validation
13. `MultipartBodyLengthLimit`
14. `MaxFileSize` en request limits
15. `KestrelServerLimits.MaxRequestBodySize`
16. File type validation (extension)
17. File type validation (content type / MIME)
18. Magic number validation (file signature)
19. Security: prevent path traversal attacks
20. Security: sanitize file names
21. Generate unique file names (GUID)
22. `Path.GetRandomFileName()`
23. Save to disk: `IWebHostEnvironment.WebRootPath`
24. Save to disk: custom path
25. `wwwroot/uploads` folder
26. Static files serving para uploads
27. Static files middleware: `app.UseStaticFiles()`
28. Serve files outside wwwroot con `FileProvider`
29. `PhysicalFileProvider` y `EmbeddedFileProvider`
30. Save to database: `byte[]` column
31. Save to database: `varbinary(max)`
32. Save to Azure Blob Storage
33. `Azure.Storage.Blobs` NuGet package
34. `BlobServiceClient` y `BlobContainerClient`
35. Upload to blob: `UploadAsync(stream)`
36. Download from blob: `DownloadAsync()`
37. Blob metadata (content type, properties)
38. Azure Blob Storage: access levels (private, blob, container)
39. SAS tokens (Shared Access Signature)
40. SAS token generation para download URLs
41. Save to AWS S3
42. `AWSSDK.S3` NuGet package
43. Upload/download con S3
44. Presigned URLs para S3
45. File download con `FileContentResult`
46. `return File(bytes, contentType, fileName)`
47. File download con `FileStreamResult`
48. `return File(stream, contentType, fileName)`
49. File download con `PhysicalFileResult`
50. `return PhysicalFile(path, contentType, fileName)`
51. `VirtualFileResult`
52. `FileContentResult` vs `FileStreamResult`
53. Content-Disposition header (attachment vs inline)
54. Inline display (PDF en navegador)
55. Download as attachment
56. Range requests para large files
57. `[EnableRangeProcessing]`
58. Partial content (206)
59. Streaming large file uploads
60. `DisableFormValueModelBindingAttribute`
61. `MultipartReader` para streaming directo
62. Kestrel streaming
63. IFormFile buffering
64. `MultipartBodyLengthLimit` vs `MaxRequestBodySize`
65. Chunked file upload
66. Resumable uploads (TUS protocol concept)
67. File upload progress tracking (JavaScript)
68. AJAX file upload con `fetch`
69. AJAX file upload con `XMLHttpRequest` (progress)
70. Drag and drop file upload
71. File upload en Blazor con `InputFile`
72. File preview before upload
73. Image upload y resize
74. Image processing con `ImageSharp` o `SkiaSharp`
75. Thumbnail generation
76. Watermark addition
77. File conversion (e.g., DOCX to PDF)
78. CSV file import/export
79. Excel file import/export con `ClosedXML` o `EPPlus`
80. PDF generation con `Rotativa.AspNetCore`
81. PDF generation con `DinkToPdf`
82. PDF generation con QuestPDF
83. ZIP file creation y download
84. `System.IO.Compression.ZipArchive`
85. ZIP file extraction
86. Virus scanning de uploads (ClamAV)
87. File storage best practices
88. File naming conventions
89. Directory structure para files
90. File versioning
91. File cleanup (auto-delete old files)
92. File storage quotas
93. CDN para servir archivos
94. Azure CDN con Blob Storage
95. CloudFront con S3
96. File upload testing
97. Integration tests con file uploads
98. Mock file storage en tests
99. File upload security checklist
100. Best practices de file handling en producción

---

## MÓDULO 37: HEALTH CHECKS

**Descripción:** Aprenderás a implementar health checks en ASP.NET Core para monitorear el estado de tu aplicación y sus dependencias. Es esencial para orquestadores como Kubernetes y para operaciones de DevOps.

1. ¿Qué son los Health Checks?
2. `IHealthCheck` interface
3. `CheckHealthAsync(HealthCheckContext, CancellationToken)`
4. `HealthCheckResult`: Healthy, Unhealthy, Degraded
5. `AddHealthChecks()` en `Program.cs`
6. `MapHealthChecks("/health")`
7. `HealthCheckOptions`
8. `ResponseWriter` personalizado
9. `UIResponseWriter` para JSON responses
10. Health check de base de datos: `AddDbContextCheck<T>()`
11. Health check de SQL Server: `AddSqlServer(connectionString)`
12. Health check de Redis: `AddRedis(connectionString)`
13. Health check de RabbitMQ
14. Health check de HTTP endpoints: `AddUrlGroup(uri)`
15. Health check de Azure Blob Storage
16. Health check de AWS services
17. Custom health check: implementar `IHealthCheck`
18. Health check con tags (categorías)
19. Filtering por tags: `Predicate = r => r.Tags.Contains("ready")`
20. Liveness vs Readiness probes
21. `/health/live` - ¿está la app corriendo?
22. `/health/ready` - ¿está la app lista para recibir tráfico?
23. Separar endpoints por tags
24. Health check con DI (inyectar servicios)
25. Health check con timeout
26. `HealthCheckRegistration.Timeout`
27. Health check que retorna data (`HealthCheckResult.Data`)
28. Custom response writer: `WriteResponse`
29. JSON response con detalles
30. Health check UI: `AspNetCore.HealthChecks.UI`
31. HealthChecks UI dashboard
32. UI storage (InMemory, SQL Server)
33. UI push endpoint
34. Health check notifications (webhooks, Slack, Teams)
35. `HealthChecks.Publisher.ApplicationInsights`
36. `HealthChecks.Publisher.Prometheus`
37. Health checks en Kubernetes
38. `livenessProbe` y `readinessProbe`
39. `initialDelaySeconds`, `periodSeconds`
40. `httpGet` probe configuration
41. Health checks en Docker Compose
42. Health checks en Azure App Service
43. Health check en load balancers
44. Health check con background service status
45. Health check de disk space
46. Health check de memory usage
47. Health check de CPU usage
48. Health check de external API
49. Health check de message queue
50. Health check de cache
51. Health check de search engine (Elasticsearch)
52. Health check de email service
53. Health check de file storage
54. Health check de certificate expiration
55. Health check de DNS resolution
56. Health check de network connectivity
57. Health check con authentication
58. `RequireAuthorization()` en health endpoints
59. API key para health endpoints
60. Health check y middleware ordering
61. Health check logging
62. Health check metrics
63. Health check history
64. Health check degradation strategies
65. Degraded vs Unhealthy: cuándo usar cada uno
66. Health check aggregation
67. Composite health check
68. Health check dependencies graph
69. Health check y graceful shutdown
70. Health check en microservices
71. Service mesh health checks
72. Consul health checks
73. Health check y circuit breaker
74. Health check con caching (no checkear cada request)
75. Health check frequency tuning
76. Health check y zero-downtime deployment
77. Health check en blue-green deployment
78. Health check en canary deployment
79. Health check y rolling updates
80. Health check endpoint naming conventions
81. Health check y security (no exponer info sensible)
82. Health check y rate limiting
83. Health check y output caching
84. Health check y CORS
85. Health check en IIS
86. Health check en Nginx
87. Health check en Azure Front Door
88. Health check en AWS ALB
89. Health check monitoring tools
90. Grafana dashboards con health check data
91. Prometheus metrics de health checks
92. AlertManager rules para health checks
93. PagerDuty integration
94. Slack notifications
95. Email alerting
96. Health check testing
97. Unit testing health checks
98. Integration testing health checks
99. Health check documentation
100. Best practices de health checks en producción

---

## MÓDULO 38: RATE LIMITING

**Descripción:** Aprenderás a implementar rate limiting en ASP.NET Core para proteger tu API contra abuso, ataques de fuerza bruta, y sobrecarga. .NET 7+ incluye rate limiting integrado en el framework.

1. ¿Qué es Rate Limiting?
2. ¿Por qué necesitas rate limiting?
3. Attack scenarios: DDoS, brute force, scraping
4. Rate limiting strategies overview
5. Fixed Window Limiter
6. Sliding Window Limiter
7. Token Bucket Limiter
8. Concurrency Limiter
9. `System.Threading.RateLimiting` NuGet package
10. `AddRateLimiter()` en `Program.cs`
11. `UseRateLimiter()` middleware
12. `RateLimiterOptions`
13. `AddFixedWindowLimiter()`
14. `FixedWindowRateLimiterOptions`
15. `PermitLimit` - máximo de requests
16. `Window` - ventana de tiempo
17. `QueueProcessingOrder`
18. `QueueLimit`
19. `AddSlidingWindowLimiter()`
20. `SlidingWindowRateLimiterOptions`
21. `SegmentsPerWindow`
22. `AddTokenBucketLimiter()`
23. `TokenBucketRateLimiterOptions`
24. `TokenLimit`
25. `ReplenishmentPeriod`
26. `TokensPerPeriod`
27. `AutoReplenishment`
28. `AddConcurrencyLimiter()`
29. `ConcurrencyLimiterOptions`
30. `PermitLimit` (concurrent requests)
31. Named rate limiters
32. `AddRateLimiter("fixed", options => ...)`
33. Per-endpoint rate limiting: `.RequireRateLimiting("fixed")`
34. Global rate limiting
35. Partitioned rate limiting (per user, per IP)
36. `PartitionedRateLimiter.Create()`
37. `HttpContext`-based partitioning
38. Per-user rate limiting (by claim)
39. Per-IP rate limiting
40. Per-API-key rate limiting
41. Custom partition key
42. `RateLimitPartition.GetFixedWindowLimiter()`
43. `RateLimitPartition.GetSlidingWindowLimiter()`
44. `RateLimitPartition.GetTokenBucketLimiter()`
45. `RateLimitPartition.GetConcurrencyLimiter()`
46. `RateLimitPartition.GetNoLimiter()` - exempt
47. Rate limit response: 429 Too Many Requests
48. Custom rejection response
49. `OnRejected` callback
50. `Retry-After` header
51. `X-RateLimit-Limit` header
52. `X-RateLimit-Remaining` header
53. `X-RateLimit-Reset` header
54. Custom headers en rate limit response
55. `RateLimiterOptions.RejectionStatusCode`
56. Rate limiting en Minimal APIs
57. `.RequireRateLimiting()` en route groups
58. Rate limiting en MVC controllers
59. `[EnableRateLimiting("policy")]` attribute
60. `[DisableRateLimiting]` attribute
61. Rate limiting con distributed cache (Redis)
62. Custom `RateLimiter` implementation
63. `IRateLimiter` interface
64. `RateLimitLease`
65. `TokenBucketRateLimiter`
66. `FixedWindowRateLimiter`
67. `SlidingWindowRateLimiter`
68. `ConcurrencyLimiter`
69. Composite rate limiters
70. Rate limiting y authentication
71. Different limits para authenticated vs anonymous
72. Different limits por role/tier
73. Rate limiting y API keys
74. Rate limiting y IP address (X-Forwarded-For)
75. Rate limiting behind proxy
76. Rate limiting y health checks (exempt)
77. Rate limiting y static files (exempt)
78. Rate limiting y middleware ordering
79. Rate limiting testing
80. Integration tests con rate limiting
81. Load testing para validate limits
82. Rate limiting en production
83. Rate limiting en API Gateway (YARP, Azure APIM)
84. Redis-based distributed rate limiting
85. `StackExchange.Redis` para rate limiting
86. Sliding window con Redis sorted sets
87. Rate limiting y microservices
88. Centralized rate limiting
89. Rate limiting policies per service
90. Rate limiting y monitoring
91. Metrics: requests rejected, allowed
92. Grafana dashboards para rate limiting
93. Alert on rate limit hits
94. Rate limiting y user experience
95. Graceful degradation
96. Rate limit exceeded page (MVC)
97. Rate limit exceeded JSON (API)
98. Client-side handling de 429
99. Retry with exponential backoff
100. Best practices de rate limiting en producción

---

## MÓDULO 39: OUTPUT CACHING

**Descripción:** Aprenderás Output Caching, la nueva feature de .NET 7 que cachea las respuestas HTTP en el servidor. A diferencia de Response Caching, Output Caching siempre almacena en el servidor y ofrece más control y mejor rendimiento.

1. ¿Qué es Output Caching?
2. Output Caching vs Response Caching
3. Response Caching: cachea en cliente (Cache-Control) y servidor (middleware)
4. Output Caching: siempre cachea en servidor
5. `AddOutputCache()` en `Program.cs`
6. `UseOutputCache()` middleware
7. `[OutputCache]` attribute en endpoints
8. `OutputCacheOptions`
9. Default policy
10. Named policies: `options.AddPolicy("MyPolicy", ...)`
11. `OutputCachePolicyBuilder`
12. `.Expire(TimeSpan)` - tiempo de expiración
13. `.SetVaryByQuery("key")` - variar por query parameter
14. `.SetVaryByRouteValue("id")` - variar por route value
15. `.SetVaryByHeader("Accept-Language")` - variar por header
16. `.SetVaryByHeader("Authorization")` - para auth-specific cache
17. `.Tag("products")` - para invalidation
18. `.With(c => c.HttpContext.User.Identity.IsAuthenticated)` - conditional
19. Output caching por endpoint en Minimal APIs
20. `.CacheOutput("policyName")`
21. `.CacheOutput(builder => builder.Expire(...))`
22. Output caching en MVC controllers
23. `[OutputCache(Duration = 60)]`
24. `[OutputCache(PolicyName = "MyPolicy")]`
25. Vary by query keys
26. Vary by multiple query keys
27. Vary by route values
28. Vary by headers
29. Vary by custom value: `SetVaryByCustom`
30. Vary by user (authentication)
31. Cache key components
32. Default cache key generation
33. Custom cache key generation
34. `IOutputCacheStore` para invalidation programática
35. `EvictByTagAsync("tag")` - invalidar por tag
36. Cache invalidation strategies
37. Time-based invalidation
38. Tag-based invalidation
39. Event-based invalidation
40. Invalidate after data modification
41. Cache y data consistency
42. Bypass cache: `OutputCacheAttribute` options
43. `NoStore = true`
44. `VaryByQueryKeys = new[] { "*" }`
45. Cache revalidation
46. `ETag` y cache revalidation
47. `Last-Modified` y cache revalidation
48. `If-None-Match` handling
49. `304 Not Modified` responses
50. Output caching y authentication
51. Don't cache authenticated responses (usually)
52. Cache per user scenarios
53. Output caching y authorization
54. Output caching y CORS
55. Output caching y health checks
56. Output caching y response compression
57. Middleware ordering: OutputCache after Routing
58. `IOutputCacheStore` internals
59. Custom `IOutputCacheStore` (e.g., Redis)
60. Distributed output caching
61. Output caching en multi-instance deployment
62. Cache warming
63. Pre-cache popular pages
64. Background cache refresh
65. Cache hit/miss monitoring
66. Cache metrics
67. X-Cache header (custom)
68. Cache diagnostics
69. Output caching y Razor pages
70. Output caching en Blazor SSR
71. Output caching y SignalR (not applicable)
72. Output caching y streaming (not applicable)
73. Output caching y file downloads
74. Output caching y JSON responses
75. Output caching y HTML pages
76. Cache size limits
77. Memory pressure y eviction
78. LRU eviction
79. Output caching en microservices
80. Edge caching (CDN) vs server caching
81. Multi-layer caching
82. CDN + Output Cache
83. Varnish como reverse proxy cache
84. Testing output caching
85. Integration tests con output caching
86. Verify cache hit/miss en tests
87. Cache key verification
88. Cache invalidation testing
89. Performance testing con output caching
90. Benchmarks: con y sin cache
91. Output caching y API versioning
92. Output caching y pagination
93. Output caching y search
94. Output caching y filters
95. Cache profiles (reusable policies)
96. Global output cache policy
97. Per-endpoint policy override
98. Output caching y GDPR (don't cache personal data)
99. Output caching y compliance
100. Best practices de output caching

---

## MÓDULO 40: gRPC EN ASP.NET CORE

**Descripción:** Aprenderás gRPC, el framework de RPC de alto rendimiento de Google, integrado en ASP.NET Core. Ideal para comunicación entre microservicios donde el rendimiento y la tipificación fuerte son prioritarios.

1. ¿Qué es gRPC? (Google Remote Procedure Call)
2. gRPC vs REST: diferencias fundamentales
3. HTTP/2 como base de gRPC
4. Protocol Buffers (protobuf): formato de serialización
5. `.proto` files: definición de servicios y mensajes
6. `syntax = "proto3"`
7. Message types en protobuf
8. Scalar types (string, int32, bool, etc.)
9. Nested messages
10. Repeated fields (listas)
11. Enum types
12. Oneof (unión de campos)
13. Map fields
14. Service definition: `service ProductService { ... }`
15. RPC methods: `rpc GetProduct (ProductRequest) returns (Product)`
16. gRPC patterns:
17. Unary RPC (request-response)
18. Server streaming
19. Client streaming
20. Bidirectional streaming
21. `Grpc.AspNetCore` NuGet package
22. `Grpc.Tools` para code generation
23. `Google.Protobuf` NuGet package
24. Proto file en el proyecto
25. `.proto` file build action: `Protobuf`
26. Generated C# code desde `.proto`
27. Implementar un gRPC service: heredar de `ProductService.ProductServiceBase`
28. Override generated methods
29. `ServerCallContext` parameter
30. Return generated message types
31. `app.MapGrpcService<ProductServiceImpl>()`
32. gRPC endpoint configuration
33. HTTP/2 configuration en Kestrel
34. `ListenAnyIP(5001, o => o.Protocols = HttpProtocols.Http2)`
35. TLS/SSL para gRPC
36. gRPC client: `Grpc.Net.Client`
37. `GrpcChannel.ForAddress()`
38. Create client from channel
39. Call unary methods
40. Call streaming methods
41. Call server streaming
42. Call client streaming
43. Call bidirectional streaming
44. `AsyncServerStreamingCall`
45. `AsyncClientStreamingCall`
46. `AsyncDuplexStreamingCall`
47. gRPC client con DI
48. `AddGrpcClient<T>()`
49. `IHttpClientFactory` con gRPC clients
50. Deadline y cancellation
51. `CallOptions` con deadline
52. `CancellationToken` propagation
53. gRPC metadata (headers)
54. `Metadata` collection
55. Send metadata desde client
56. Read metadata en server
57. Response trailers
58. Error handling: `RpcException`
59. `StatusCode` (NotFound, InvalidArgument, etc.)
60. Custom error details
61. `Status` y `Trailers`
62. gRPC interceptors: client-side
63. gRPC interceptors: server-side
64. `Interceptor` base class
65. Logging interceptor
66. Authentication interceptor (add token)
67. Tracing interceptor
68. gRPC y authentication
69. JWT authentication con gRPC
70. Certificate authentication con gRPC
71. `[Authorize]` en gRPC services
72. gRPC y DI
73. Inject services en gRPC implementation
74. Scoped vs Singleton services en gRPC
75. gRPC y EF Core
76. DbContext en gRPC services
77. gRPC health checks
78. `Grpc.AspNetCore.HealthChecks`
79. `MapGrpcHealthChecks()`
80. gRPC reflection
81. `Grpc.AspNetCore.Server.Reflection`
82. `MapGrpcReflectionService()`
83. grpcurl CLI tool
84. gRPC con Postman
85. gRPC con BloomRPC
86. gRPC-Web: gRPC en browsers
87. `Grpc.AspNetCore.Web`
88. `UseGrpcWeb()`
89. gRPC-Web con Blazor WASM
90. gRPC y load balancing
91. Client-side load balancing
92. gRPC y service discovery
93. gRPC con Kubernetes
94. gRPC con Envoy proxy
95. gRPC con YARP
96. gRPC performance tuning
97. Connection pooling
98. Channel options
99. gRPC con Native AOT
100. Best practices de gRPC en producción

---

## MÓDULO 41: CLEAN ARCHITECTURE

**Descripción:** Aprenderás a estructurar aplicaciones ASP.NET Core siguiendo Clean Architecture (también conocida como Onion Architecture o Hexagonal Architecture). Separarás las dependencias de forma que tu dominio de negocio sea independiente de frameworks, bases de datos, y UI.

1. ¿Qué es Clean Architecture? (Robert C. Martin)
2. The Dependency Rule: dependencias apuntan hacia adentro
3. Las 4 capas: Domain, Application, Infrastructure, Presentation
4. Domain Layer: entidades, value objects, domain events
5. Application Layer: use cases, DTOs, interfaces
6. Infrastructure Layer: EF Core, email, file storage, APIs externas
7. Presentation Layer: controllers, views, API endpoints
8. Domain es la capa más interna (no depende de nada)
9. Application depende de Domain
10. Infrastructure implementa interfaces de Application
11. Presentation depende de Application
12. Proyecto por capa vs feature folders
13. `MyApp.Domain` project
14. `MyApp.Application` project
15. `MyApp.Infrastructure` project
16. `MyApp.Api` o `MyApp.Web` project
17. Referencias entre proyectos
18. Domain Entities y Entity base class
19. Value Objects
20. Domain Events
21. Domain Services
22. Aggregate Root
23. Aggregate y bounded context
24. Specification pattern
25. Repository pattern: `IRepository<T>`
26. `IAsyncRepository<T>`
27. Repository implementation en Infrastructure
28. Unit of Work pattern
29. `IUnitOfWork` interface
30. `SaveChangesAsync` como Unit of Work
31. Application layer: Use Cases / Commands / Queries
32. DTOs: Data Transfer Objects
33. Mapping: Entity ↔ DTO (AutoMapper, Mapster)
34. Interfaces en Application layer
35. `IProductRepository` en Application
36. `ProductRepository` en Infrastructure
37. DI registration: `services.AddScoped<IProductRepository, ProductRepository>()`
38. Application services (command/query handlers)
39. Service layer pattern
40. FluentValidation en Application layer
41. Logging abstraction en Application
42. `IApplicationLogger`
43. Exception handling per layer
44. Domain exceptions
45. Application exceptions
46. Infrastructure exceptions
47. Presentation error mapping
48. API layer: controllers que llaman a use cases
49. Thin controllers: solo delegan al service/use case
50. Vertical Slice Architecture (alternativa)
51. Feature folders con vertical slices
52. Modularity: módulos dentro de la app
53. Module registration pattern
54. `AddProductsModule(this IServiceCollection services)`
55. `MapProductsEndpoints(this IEndpointRouteBuilder app)`
56. Cross-cutting concerns: logging, caching, auth
57. Cross-cutting en Infrastructure
58. Middleware como cross-cutting
59. Filtros como cross-cutting
60. Dependency injection setup por capa
61. `builder.Services.AddApplication()`
62. `builder.Services.AddInfrastructure()`
63. Clean Architecture con EF Core
64. DbContext en Infrastructure
65. Migrations en Infrastructure o proyecto separado
66. Clean Architecture con Dapper
67. Clean Architecture con API
68. Clean Architecture con MVC
69. Clean Architecture con Blazor
70. Clean Architecture con Minimal APIs
71. Clean Architecture con gRPC
72. Testing por capa
73. Domain testing (pure unit tests)
74. Application testing (mocked dependencies)
75. Infrastructure testing (integration tests con DB)
76. Presentation testing (controller tests)
77. Clean Architecture template (`JasonTaylor`)
78. `dotnet new ca` template
79. Onion Architecture vs Clean Architecture
80. Hexagonal Architecture (Ports and Adapters)
81. Ports: interfaces en Application
82. Adapters: implementaciones en Infrastructure
83. Primary adapters (API, UI)
84. Secondary adapters (DB, Email)
85. Comparison: Clean vs Layered vs Onion
86. When NOT to use Clean Architecture (small apps)
87. Clean Architecture y DDD juntos
88. Clean Architecture y CQRS juntos
89. Clean Architecture y Event Sourcing
90. Monolith-first approach
91. Modular monolith
92. Extracting modules a microservices
93. Clean Architecture y multi-tenancy
94. Clean Architecture y feature flags
95. Code organization best practices
96. Naming conventions per layer
97. SOLID principles en cada capa
98. Encapsulation boundaries
99. Clean Architecture con .NET Aspire
100. Real-world Clean Architecture project structure

---

## MÓDULO 42: CQRS CON MEDIATR

**Descripción:** Aprenderás el patrón CQRS (Command Query Responsibility Segregation) usando la librería MediatR. Separarás la lógica de lectura y escritura en objetos independientes, resultando en un código más limpio, testeable y escalable.

1. ¿Qué es CQRS? (Greg Young)
2. Separar Commands (escritura) de Queries (lectura)
3. Command: modifica estado, no retorna datos (o retorna ID)
4. Query: lee datos, no modifica estado
5. MediatR: librería para implementar mediator pattern
6. `MediatR` NuGet package (MediatR en NuGet, ahora Carter o Wolverine)
7. `AddMediatR(cfg => cfg.RegisterServicesFromAssembly(...))`
8. `IRequest<TResponse>`: command/query definition
9. `IRequestHandler<TRequest, TResponse>`: handler
10. `IMediator` interface
11. `mediator.Send(request)`: enviar command o query
12. Command: `CreateProductCommand : IRequest<int>`
13. Command Handler: `CreateProductCommandHandler : IRequestHandler<CreateProductCommand, int>`
14. Query: `GetProductByIdQuery : IRequest<ProductDto>`
15. Query Handler: `GetProductByIdQueryHandler : IRequestHandler<GetProductByIdQuery, ProductDto>`
16. Handlers con DI (inject repositorios, DbContext, etc.)
17. FluentValidation con MediatR: `IPipelineBehavior<TRequest, TResponse>`
18. `ValidationBehavior` pipeline
19. `AddTransient(typeof(IPipelineBehavior<,>), typeof(ValidationBehavior<,>))`
20. Logging behavior: pipeline de logging
21. Performance behavior: medir tiempo de ejecución
22. Caching behavior: cachear queries
23. Transaction behavior: wrap commands en transacción
24. `IPipelineBehavior` ordering
25. Pipeline behaviors como middleware
26. `RequestExceptionHandler<TRequest, TResponse, TException>`
27. `IRequestExceptionHandler` para manejo de errores
28. Notifications: `INotification`
29. `IRequestPreProcessor<TRequest>` y `IRequestPostProcessor<TRequest>`
30. Notification handlers: `INotificationHandler<TNotification>`
31. `mediator.Publish(notification)`
32. Multiple handlers para una notificación
33. Domain events con MediatR notifications
34. Domain event dispatching desde `SaveChanges`
35. `IDomainEvent : INotification`
36. `ProductCreatedEvent : IDomainEvent`
37. Dispatch events after save
38. CQRS con EF Core
39. Shared DbContext para commands y queries
40. Separate DbContext para read y write (advanced)
41. Dapper para queries (read model)
42. EF Core para commands (write model)
43. Read model optimization (denormalized tables)
44. Write model normalizado
45. Projections: entity a DTO en queries
46. AutoMapper con MediatR
47. Mapster como alternativa a AutoMapper
48. Manual mapping (sin librería)
49. Vertical Slice Architecture con MediatR
50. One handler per feature
51. Feature folder organization
52. Controller simplificado con MediatR
53. `return await _mediator.Send(new GetProductsQuery());`
54. Minimal API con MediatR
55. `app.MapGet("/products", async (IMediator mediator) => await mediator.Send(...))`
56. Testing command handlers
57. Testing query handlers
58. Mock repositories en handlers
59. Mock `IMediator` en controllers
60. Testing pipeline behaviors
61. Testing notifications
62. Testing domain events
63. Carter library como alternativa para routing
64. `Carter` NuGet: módulos con endpoints
65. Wolverine como alternativa a MediatR
66. Wolverine: message-based, no mediator pattern exacto
67. MediatR v12+ changes
68. `MediatR` se volvió pago/comercial en algunas versiones
69. Alternativas: Wolverine, Brighter, MassTransit
70. CQRS sin MediatR (manual implementation)
71. Command/Query objects y dispatcher manual
72. CQRS en microservices
73. Event sourcing con CQRS
74. Event store y event stream
75. Projections y read models
76. CQRS y eventual consistency
77. CQRS y sagas (process managers)
78. CQRS y API layer
79. CQRS patterns comparison
80. Command validation con FluentValidation
81. `AbstractValidator<CreateProductCommand>`
82. Validation errors a ProblemDetails
83. Custom validation behavior
84. Authorization behavior con MediatR
85. `IAuthorizationRequest`
86. `AuthorizationBehavior` pipeline
87. Pre/Post processors
88. Auditing con MediatR
89. Logging de commands ejecutados
90. CQRS performance considerations
91. Query optimization para read models
92. Caching en query handlers
93. Pagination en queries
94. Sorting en queries
95. Filtering en queries
96. CQRS y Event-Driven Architecture
97. CQRS y Domain-Driven Design
98. CQRS y modular monolith
99. Real-world CQRS examples
100. Best practices de CQRS con MediatR

---

## MÓDULO 43: DOMAIN-DRIVEN DESIGN (DDD)

**Descripción:** Aprenderás los conceptos de Domain-Driven Design y cómo aplicarlos en aplicaciones ASP.NET Core. DDD se centra en modelar el dominio del negocio de forma que el código refleje fielmente las reglas y procesos del negocio.

1. ¿Qué es Domain-Driven Design? (Eric Evans)
2. Strategic Design vs Tactical Design
3. Ubiquitous Language: lenguaje compartido entre devs y domain experts
4. Bounded Context: frontera de un subdominio
5. Context Mapping: relaciones entre bounded contexts
6. Subdomains: Core, Supporting, Generic
7. Entities: objetos con identidad
8. Entity base class: `Id` property
9. Entity equality basada en `Id`
10. Value Objects: objetos inmutables sin identidad
11. Value Object equality basada en propiedades
12. Ejemplos: `Address`, `Money`, `DateRange`
13. `record` types para Value Objects (C# 9)
14. Aggregate: cluster de entidades tratadas como unidad
15. Aggregate Root: la entidad principal del aggregate
16. Aggregate invariants (reglas de negocio que se deben mantener)
17. References entre aggregates por ID (no por object reference)
18. Aggregate boundaries: keep them small
19. Domain Events: representan algo que ocurrió en el dominio
20. `IDomainEvent`
21. Domain Event dispatching
22. MediatR para domain events
23. Domain Services: lógica de negocio que no pertenece a una entity
24. `IPricingService`
25. Domain Services vs Application Services
26. Factory pattern en DDD
27. Repository pattern en DDD: uno por Aggregate Root
28. `IProductRepository` (para el Aggregate Root `Product`)
29. Specification pattern: encapsular reglas de consulta
30. `ISpecification<T>`
31. `And()`, `Or()`, `Not()` specifications
32. Ardalis.Specification library
33. Anti-Corruption Layer (ACL)
34. Context Mapping patterns: Shared Kernel, Customer-Supplier, etc.
35. Conformist pattern
36. Open Host Service
37. Published Language
38. DDD Tactical Patterns implementation en C#
39. Strongly-typed IDs
40. `ProductId` como wrapper de `int` o `Guid`
41. `ValueObject` base class
42. `AggregateRoot` base class
43. Domain exceptions: `DomainException`
44. Guard clauses (precondiciones)
45. `Guard.Against.NullOrEmpty(name, nameof(name))`
46. Ardalis.GuardClauses library
47. DDD con EF Core
48. Owned types para Value Objects
49. Complex types (.NET 8)
50. Value Object persistence con EF Core
51. Private setters y backing fields
52. Encapsulated collections
53. EF Core configuration para aggregates
54. DDD y Clean Architecture juntos
55. DDD en Application Layer
56. DDD en Domain Layer
57. DDD en Infrastructure Layer
58. Bounded Context y proyectos separados
59. Microservices como Bounded Contexts
60. Event-Driven Architecture con DDD
61. Domain Events: in-process vs cross-process
62. Integration Events vs Domain Events
63. Event bus para integration events
64. Outbox pattern
65. Inbox pattern
66. Sagas / Process Managers
67. Eventual consistency entre aggregates
68. Consistency boundaries
69. DDD y CQRS
70. DDD y Event Sourcing
71. DDD y reactive programming
72. DDD en aplicaciones pequeñas: ¿cuándo es overkill?
73. DDD lite: usar solo algunos patterns
74. DDD y personas: la parte más importante
75. Event storming: técnica para descubrir domain events
76. Event storming workshop format
77. Domain modeling sessions
78. DDD y code reviews
79. DDD y testing (tests como especificación)
80. BDD (Behavior-Driven Development) con DDD
81. DDD y refactoring
82. Legacy code y DDD
83. Migrar de Transaction Script a DDD
84. DDD y multi-tenancy
85. DDD y internationalization
86. DDD y auditing
87. DDD y security
88. DDD y API design
89. DDD en microservices
90. DDD patterns en .NET libraries
91. Aggregate design guidelines
92. Event naming conventions
93. Value Object design guidelines
94. Entity design guidelines
95. Repository design guidelines
96. Service design guidelines
97. DDD y SOLID principles
98. DDD reference architecture (eShopOnWeb)
99. Implementing DDD (book by Vaughn Vernon)
100. Best practices de DDD en .NET

---

## MÓDULO 44: MICROSERVICIOS CON .NET

**Descripción:** Aprenderás a diseñar, construir, y desplegar aplicaciones basadas en microservicios con ASP.NET Core. Desde la comunicación entre servicios hasta la resiliencia, observabilidad, y despliegue en contenedores.

1. ¿Qué son los microservicios?
2. Monolith vs Microservices
3. ¿Cuándo NO usar microservicios?
4. Monolith-first approach
5. Modular monolith como paso intermedio
6. Decomposition strategies (por subdominio, por capability)
7. Bounded Context = Microservice (ideal)
8. Service communication: Synchronous (HTTP, gRPC)
9. Service communication: Asynchronous (message queues)
10. REST APIs entre servicios (síncrono)
11. gRPC entre servicios (síncrono, alto rendimiento)
12. HttpClient entre servicios
13. `IHttpClientFactory` para HttpClient management
14. Typed HTTP clients
15. Named HTTP clients
16. Resilience con Polly
17. Retry policy
18. Circuit breaker pattern
19. Bulkhead isolation
20. Timeout policy
21. Polly v8 resilience pipelines
22. `AddResilienceHandler()` (.NET 8)
23. Message queues: RabbitMQ
24. Message queues: Azure Service Bus
25. Message queues: Amazon SQS
26. MassTransit: message bus abstraction
27. MassTransit con RabbitMQ
28. MassTransit: `IPublishEndpoint`, `ISendEndpoint`
29. MassTransit: request/response
30. MassTransit: sagas (state machines)
31. `AddMassTransit()` configuration
32. Consumer pattern en MassTransit
33. Message patterns: Fire-and-forget, Request-Response, Pub/Sub
34. Integration events entre servicios
35. Event bus pattern
36. Outbox pattern: garantizar entrega
37. Inbox pattern: garantizar procesamiento idempotente
38. Eventual consistency
39. Saga pattern: orchestración vs coreografía
40. API Gateway: concepto y necesidad
41. YARP como API Gateway
42. YARP: configuración de routes
43. YARP: load balancing strategies
44. YARP: health checks
45. YARP: transforms
46. Azure API Management
47. AWS API Gateway
48. Service discovery
49. Consul para service discovery
50. DNS-based service discovery en Kubernetes
51. Configuration en microservices
52. Centralized configuration (Azure App Configuration)
53. Distributed configuration
54. Service mesh (Istio, Linkerd) - concepto
55. Service mesh: sidecar pattern
56. Distributed tracing
57. OpenTelemetry en microservices
58. Correlation ID propagation
59. W3C TraceContext
60. Centralized logging
61. ELK Stack (Elasticsearch, Logstash, Kibana)
62. Grafana Loki
63. Structured logging en microservices
64. Health checks en microservices
65. Kubernetes liveness/readiness probes
66. Microservices deployment con Docker
67. Dockerfile para ASP.NET Core microservice
68. Multi-stage Docker builds
69. Docker Compose para local development
70. Docker Compose con múltiples servicios
71. Kubernetes basics
72. Kubernetes Deployments
73. Kubernetes Services
74. Kubernetes Ingress
75. Kubernetes ConfigMaps y Secrets
76. Helm charts
77. CI/CD para microservices
78. Independent deployment por servicio
79. Contract testing entre servicios
80. Pact para contract testing
81. End-to-end testing en microservices
82. Database per service
83. Shared database (anti-pattern)
84. Data consistency entre servicios
85. CQRS en microservices
86. DDD en microservices
87. Event sourcing en microservices
88. Idempotency en message processing
89. Exactly-once processing (impossible, use at-least-once + idempotency)
90. Dead letter queues
91. Message retry policies
92. Circuit breaker con message queues
93. Monitoring y alerting en microservices
94. Prometheus + Grafana
95. Distributed tracing con Jaeger/Zipkin
96. Chaos engineering con microservices
97. Chaos Monkey concepts
98. Microservices anti-patterns
99. Nano-services (too granular)
100. Best practices de microservices con .NET

---

## MÓDULO 45: MESSAGE QUEUES (RABBITMQ, AZURE SERVICE BUS)

**Descripción:** Dominarás el uso de colas de mensajes para comunicación asíncrona entre servicios. Aprenderás RabbitMQ local y Azure Service Bus en la nube, junto con MassTransit como abstracción que simplifica todo.

1. ¿Qué son los Message Queues?
2. Synchronous vs Asynchronous communication
3. Benefits: desacoplamiento, resiliencia, escalabilidad
4. Producer-Consumer pattern
5. Pub/Sub pattern
6. Point-to-Point messaging
7. Message Broker: concepto
8. RabbitMQ: instalación (Docker)
9. RabbitMQ: Exchange, Queue, Binding
10. Exchange types: Direct, Fanout, Topic, Headers
11. Routing keys
12. Queues: durable, exclusive, auto-delete
13. Message acknowledgment (ack/nack)
14. Message persistence
15. Prefetch count
16. Dead letter exchange
17. `RabbitMQ.Client` NuGet package (directo)
18. BasicPublish y BasicConsume
19. MassTransit: abstraction layer
20. `AddMassTransit()` con RabbitMQ
21. MassTransit: Consumers (message handlers)
22. `IConsumer<T>` interface
23. `ConsumeContext<T>`
24. MassTransit: `IPublishEndpoint` (publish events)
25. MassTransit: `ISendEndpoint` (send commands)
26. MassTransit: Request/Response pattern
27. MassTransit: `IRequestClient<T>`
28. MassTransit: sagas (state machines)
29. `SagaStateMachine<TInstance>`
30. MassTransit: retry policies
31. MassTransit: redelivery
32. MassTransit: circuit breaker
33. MassTransit: rate limiting
34. MassTransit: scheduling (delayed messages)
35. MassTransit: message filters
36. MassTransit: routing slips
37. Azure Service Bus: conceptos
38. Azure Service Bus: queues vs topics
39. Azure Service Bus: subscriptions
40. `Azure.Messaging.ServiceBus` NuGet
41. `ServiceBusClient` y `ServiceBusSender`
42. Send and receive messages
43. Message sessions
44. Peek-lock vs Receive-and-delete
45. Dead-letter queue en Azure Service Bus
46. Auto-forwarding
47. MassTransit con Azure Service Bus
48. `AddMassTransit().UsingAzureServiceBus()`
49. Amazon SQS: conceptos
50. Amazon SNS: conceptos (Pub/Sub)
51. MassTransit con Amazon SQS
52. Message design: command messages
53. Message design: event messages
54. Message contracts: shared DTOs
55. Message versioning
56. Backward compatibility
57. Message serialization (JSON, Avro, Protobuf)
58. Content-type negotiation
59. Correlation ID en messages
60. Message headers y metadata
61. Idempotency en message handling
62. Idempotency key pattern
63. Deduplication
64. Exactly-once vs at-least-once vs at-most-once
65. Transactional outbox pattern
66. `OutboxMessage` table
67. Polling publisher
68. Transactional outbox con EF Core
69. Inbox pattern para deduplication
70. Outbox con Debezium (CDC)
71. Message ordering
72. Partitioned queues para ordering
73. Fan-out: un message a múltiples consumers
74. Competing consumers: load balancing
75. Priority queues
76. Delayed/scheduled messages
77. TTL (Time to Live)
78. Message expiry
79. Poison messages y dead letter
80. Retry strategies: immediate, exponential backoff
81. Retry count limits
82. Error queues
83. Monitoring message queues
84. RabbitMQ management UI
85. Azure Service Bus metrics
86. Queue depth monitoring
87. Consumer lag monitoring
88. Alerting on queue backlog
89. Performance tuning
90. Batch message processing
91. Message compression
92. Large messages (claim-check pattern)
93. Testing message-based systems
94. Integration tests con Testcontainers (RabbitMQ)
95. MassTransit Testing helpers
96. In-memory test harness
97. Load testing message queues
98. Chaos testing para message brokers
99. Multi-region message replication
100. Best practices de message queues en producción

---

## MÓDULO 46: GRAPHQL CON HOTCHOCOLATE

**Descripción:** Aprenderás GraphQL como alternativa a REST para APIs que requieren flexibilidad en la consulta de datos. Usarás HotChocolate, la librería .NET más popular para GraphQL.

1. ¿Qué es GraphQL? (Facebook/Meta)
2. GraphQL vs REST: diferencias
3. GraphQL schema: types, queries, mutations
4. Query language: selección de campos
5. Introspection
6. GraphQL types: Scalar, Object, Enum, Input, Interface, Union
7. `HotChocolate.AspNetCore` NuGet package
8. Schema-first vs Code-first en HotChocolate
9. Code-first approach: attribute-based
10. `[QueryType]` y `[MutationType]`
11. `[GraphQLType]`
12. `builder.Services.AddGraphQLServer()`
13. `app.MapGraphQL()`
14. Banana Cakepop: GraphQL IDE
15. Type definitions con C# classes
16. `ObjectType<Product>`
17. Resolvers: cómo se resuelven los campos
18. `IResolverContext`
19. Parent resolvers y child resolvers
20. N+1 problem en GraphQL
21. DataLoader pattern
22. `BatchDataLoader`
23. `GroupDataLoader`
24. `AddDataLoader<T>()`
25. `IDataLoader`
26. Query definitions
27. Query con parámetros
28. Query con filtros
29. Filtering en HotChocolate
30. Sorting en HotChocolate
31. Paging en HotChocolate: cursor-based
32. `UsePaging()`
33. `Connection<T>` type
34. `PageInfo` type
35. Offset paging
36. `UseOffsetPaging()`
37. `[UseFiltering]`, `[UseSorting]`
38. Custom filtering
39. Mutations: create, update, delete
40. Input types para mutations
41. `InputObjectType<T>`
42. Mutation return types
43. Validation en mutations
44. Error handling en GraphQL
45. `IError` y `IErrorFilter`
46. Error extensions
47. `GraphQLException`
48. Custom error filter
49. Subscriptions en GraphQL
50. `[SubscriptionType]`
51. `ITopicEventReceiver`
52. `ITopicEventSender`
53. Pub/Sub para subscriptions
54. SignalR como transport para subscriptions
55. WebSocket transport
56. Server-Sent Events (SSE) transport
57. Authentication en GraphQL
58. `[Authorize]` en resolvers
59. Claims-based authorization
60. Policy-based authorization
61. Directive: `@authorize`
62. Custom directives
63. Schema directives
64. Runtime directives
65. Interceptors: `ITypeInterceptor`
66. Request interceptor: `IHttpRequestInterceptor`
67. Validation interceptor
68. Cost analysis: query complexity
69. `CostDirective`
70. Rate limiting por query cost
71. Persisted queries
72. Automatic persisted queries
73. Schema evolution y versioning
74. Deprecation: `@deprecated`
75. Schema registry
76. GraphQL y EF Core
77. `UseDbContext<T>()`
78. `UseFiltering()`, `UseSorting()` con EF Core
79. Projection en HotChocolate
80. `UseProjection()`
81. AutoMapper con GraphQL
82. GraphQL con MediatR
83. GraphQL con Clean Architecture
84. GraphQL con DDD
85. Testing GraphQL resolvers
86. Schema testing
87. Integration testing
88. Query testing
89. Mutation testing
90. Client code generation
91. Strawberry Shake: .NET GraphQL client
92. `dotnet graphql init`
93. Client-side queries con Strawberry Shake
94. Blazor con GraphQL
95. GraphQL y microservices
96. Federation en GraphQL
97. Apollo Federation con HotChocolate
98. Schema stitching
99. GraphQL Gateway pattern
100. Best practices de GraphQL en producción

---

## MÓDULO 47: IDENTITY, OAuth 2.0 Y OpenID Connect

**Descripción:** Aprenderás ASP.NET Core Identity para gestión de usuarios y roles, y cómo implementar flujos de autenticación modernos con OAuth 2.0 y OpenID Connect usando proveedores externos y soluciones como Duende IdentityServer.

1. ASP.NET Core Identity: ¿qué es?
2. `Microsoft.AspNetCore.Identity.EntityFrameworkCore`
3. `IdentityDbContext`
4. `IdentityUser` y `IdentityRole`
5. Custom `ApplicationUser : IdentityUser`
6. Custom `ApplicationRole : IdentityRole`
7. `UserManager<T>`
8. `SignInManager<T>`
9. `RoleManager<T>`
10. `CreateAsync(user, password)` para registro
11. `PasswordSignInAsync(user, password)` para login
12. `SignOutAsync()` para logout
13. `FindByNameAsync()`, `FindByIdAsync()`, `FindByEmailAsync()`
14. Password hashing: algoritmo y configuración
15. Password requirements: `IdentityOptions`
16. `RequiredLength`, `RequireDigit`, `RequireUppercase`
17. `AddIdentity()` y `AddEntityFrameworkStores()`
18. `AddDefaultTokenProviders()`
19. Migrations para Identity tables
20. Identity tables: AspNetUsers, AspNetRoles, etc.
21. Custom Identity tables (renombrar)
22. Roles: crear, asignar, verificar
23. `AddToRoleAsync()`, `IsInRoleAsync()`
24. Claims management
25. `AddClaimAsync()`, `GetClaimsAsync()`
26. User tokens (password reset, email confirm)
27. `GeneratePasswordResetTokenAsync()`
28. `ResetPasswordAsync()`
29. Email confirmation: `GenerateEmailConfirmationTokenAsync()`
30. `ConfirmEmailAsync()`
31. Two-factor authentication
32. `SetTwoFactorEnabledAsync()`
33. Authenticator app (TOTP)
34. `GetAuthenticatorKeyAsync()`
35. Recovery codes
36. External login providers
37. `AddGoogle()`, `AddMicrosoftAccount()`, `AddGitHub()`
38. External login flow
39. Link/Unlink external accounts
40. `GetExternalLoginInfoAsync()`
41. `ExternalLoginSignInAsync()`
42. Account lockout
43. `LockoutEnabled`, `LockoutEnd`
44. `AccessFailedCount`
45. `IsLockedOutAsync()`
46. Identity con Razor Pages (scaffolding)
47. Default Identity UI: `/Identity/Account/Login`
48. Scaffold Identity pages para customización
49. Identity API endpoints (.NET 8)
50. `MapIdentityApi<ApplicationUser>()`
51. Identity API: register, login, refresh, etc.
52. OAuth 2.0: conceptos fundamentales
53. OAuth 2.0 roles: Resource Owner, Client, Auth Server, Resource Server
54. OAuth 2.0 grant types
55. Authorization Code flow
56. Client Credentials flow
57. Resource Owner Password flow (legacy)
58. Implicit flow (deprecated)
59. Device Code flow
60. PKCE (Proof Key for Code Exchange)
61. OpenID Connect: capa sobre OAuth 2.0
62. ID Token vs Access Token
63. Claims en ID Token
64. Discovery endpoint (`.well-known/openid-configuration`)
65. UserInfo endpoint
66. Duende IdentityServer
67. `Duende.IdentityServer` NuGet
68. Configurar IdentityServer
69. Clients, Resources, Scopes
70. `AddIdentityServer()` y configuración
71. Persisted grants store
72. Configuration store
73. IdentityServer con ASP.NET Identity
74. BFF (Backend for Frontend) pattern
75. IdentityServer con SPA (BFF)
76. API resource protection
77. Scopes y claims en tokens
78. Token endpoint
79. Authorization endpoint
80. End session endpoint
81. Introspection endpoint
82. Reference tokens vs JWT
83. Azure Active Directory (Entra ID)
84. Register app en Azure
85. `AddMicrosoftIdentityWebApi()`
86. `AddMicrosoftIdentityWebApp()`
87. Azure AD B2C
88. Auth0: setup básico
89. `AddAuth0WebAppAuthentication()`
90. Firebase Authentication
91. Keycloak como Identity Provider
92. Identity y microservices
93. Token-based auth entre microservices
94. OAuth 2.0 token exchange
95. Token propagation
96. Identity testing
97. Mock identity en tests
98. Integration testing con identity
99. Security best practices para identity
100. Best practices de OAuth/OIDC en producción

---

## MÓDULO 48: TESTING (UNIT, INTEGRATION, E2E)

**Descripción:** Aprenderás a testear aplicaciones ASP.NET Core de forma completa: unit tests para lógica de negocio, integration tests para endpoints HTTP, y end-to-end tests con herramientas como Playwright. Los tests son esenciales para código de calidad y confianza en los cambios.

1. ¿Por qué testear? Beneficios y costos
2. Testing pyramid: unit, integration, e2e
3. xUnit: framework de testing para .NET
4. `dotnet new xunit` para crear proyecto de tests
5. `[Fact]` attribute: test individual
6. `[Theory]` con `[InlineData]`: parameterized tests
7. `[MemberData]` y `[ClassData]`
8. `Assert.Equal`, `Assert.NotEqual`
9. `Assert.True`, `Assert.False`
10. `Assert.Null`, `Assert.NotNull`
11. `Assert.Contains`, `Assert.DoesNotContain`
12. `Assert.Throws<T>()`
13. `Assert.ThrowsAsync<T>()`
14. FluentAssertions como alternativa
15. `result.Should().Be(expected)`
16. `result.Should().NotBeNull()`
17. `list.Should().HaveCount(3)`
18. `action.Should().Throw<Exception>()`
19. Moq: mocking framework
20. `Mock<IProductRepository>`
21. `mock.Setup(x => x.GetByIdAsync(1)).ReturnsAsync(product)`
22. `mock.Verify(x => x.GetByIdAsync(1), Times.Once)`
23. `It.IsAny<T>()`, `It.Is<T>(predicate)`
24. NSubstitute como alternativa
25. `var repo = Substitute.For<IProductRepository>()`
26. `repo.GetByIdAsync(1).Returns(product)`
27. `repo.Received().GetByIdAsync(1)`
28. Unit testing de Controllers (MVC)
29. Mock services inyectados en controller
30. Test `IActionResult` return types
31. Test `ViewResult` y su model
32. Test `JsonResult`
33. Test `RedirectToActionResult`
34. Test `NotFoundResult`, `BadRequestResult`
35. Unit testing de API Controllers
36. Test HTTP status codes
37. Test response body
38. Unit testing de Minimal API handlers
39. Unit testing de PageModels (Razor Pages)
40. Unit testing de Services (Application layer)
41. Unit testing de Domain entities
42. Unit testing de Value Objects
43. Unit testing de Domain Events
44. Unit testing de Validators (FluentValidation)
45. Unit testing de AutoMapper profiles
46. Unit testing de middleware (directo)
47. Unit testing de Tag Helpers
48. Unit testing de View Components
49. Unit testing de Background Services
50. Unit testing de gRPC services
51. Integration testing: concepto
52. `WebApplicationFactory<TProgram>`
53. `CreateClient()` para HTTP client en tests
54. `HttpClient` en integration tests
55. Testing API endpoints con HTTP client
56. Testing MVC endpoints
57. Testing Razor Pages
58. Override services en tests: `ConfigureServices`
59. Replace database con InMemory provider
60. Replace database con SQLite in-memory
61. Replace database con Testcontainers (real DB en Docker)
62. Testcontainers para SQL Server
63. Testcontainers para PostgreSQL
64. Testcontainers para RabbitMQ
65. Testcontainers para Redis
66. Integration test seed data
67. `IClassFixture<WebApplicationFactory>`
68. `ICollectionFixture` para compartir factory
69. Testing authentication en integration tests
70. `AddAuthentication("Test")` y test auth handler
71. `TestAuthHandler` implementation
72. Bypass authentication en tests
73. Testing authorization policies
74. Testing SignalR hubs
75. Testing background services con integration tests
76. Testing gRPC services
77. `GrpcChannel` con `WebApplicationFactory`
78. Testing con message queues (MassTransit test harness)
79. MassTransit `InMemoryTestHarness`
80. `TestConsumer` verification
81. bUnit para Blazor components
82. `BunitContext` y `RenderComponent<T>()`
83. Testing component parameters
84. Testing component events
85. Testing forms con bUnit
86. Testing JS interop con bUnit
87. E2E testing con Playwright
88. `Microsoft.Playwright` NuGet
89. Browser automation: navigate, click, type
90. Page object model pattern
91. E2E con Selenium (alternativa)
92. Test organization: naming conventions
93. AAA pattern: Arrange, Act, Assert
94. Test data builders
95. AutoFixture para test data
96. Code coverage: `coverlet`
97. `dotnet test --collect:"XPlat Code Coverage"`
98. ReportGenerator para reports
99. CI/CD integration: run tests en pipeline
100. Best practices de testing en ASP.NET Core

---

## MÓDULO 49: CI/CD Y DEPLOYMENT

**Descripción:** Aprenderás a configurar pipelines de CI/CD (Integración Continua / Despliegue Continuo) para aplicaciones ASP.NET Core. Cubriremos GitHub Actions, Azure DevOps, Docker, y estrategias de deployment a diferentes entornos.

1. ¿Qué es CI/CD?
2. Continuous Integration: concepto y beneficios
3. Continuous Delivery vs Continuous Deployment
4. Pipeline stages: Build → Test → Deploy
5. GitHub Actions: configuración básica
6. `.github/workflows/dotnet.yml`
7. `actions/checkout`, `actions/setup-dotnet`
8. `dotnet restore`, `dotnet build`, `dotnet test`
9. `dotnet publish`
10. Artifacts: upload/download
11. Environment variables en GitHub Actions
12. Secrets en GitHub Actions
13. Matrix strategy (multiple OS, multiple .NET versions)
14. GitHub Actions: deploy a Azure App Service
15. `azure/webapps-deploy` action
16. GitHub Actions: deploy a Docker Hub
17. `docker/build-push-action`
18. GitHub Actions: deploy a Azure Container Registry
19. Azure DevOps: Azure Pipelines
20. `azure-pipelines.yml` configuration
21. Stages, Jobs, Steps
22. Build pipeline
23. Test pipeline
24. Release pipeline
25. Azure DevOps: deploy a App Service
26. Azure DevOps: deploy a Kubernetes
27. Docker para ASP.NET Core
28. Dockerfile: multi-stage build
29. `mcr.microsoft.com/dotnet/sdk:8.0` para build
30. `mcr.microsoft.com/dotnet/aspnet:8.0` para runtime
31. `.dockerignore` file
32. `docker build -t myapp .`
33. `docker run -p 8080:8080 myapp`
34. Docker Compose: multi-container
35. `docker-compose.yml` con app + database + redis
36. Docker Compose override para development
37. Docker networking
38. Docker volumes para data persistence
39. Docker y environment variables
40. Docker y configuration
41. Docker y health checks
42. Docker registry: Docker Hub, ACR, ECR
43. Azure App Service: deployment
44. Azure App Service: slots (staging, production)
45. Azure App Service: slot swapping
46. Azure App Service: configuration y app settings
47. Azure App Service: connection strings
48. Azure Container Apps
49. Azure Container Instances
50. Azure Kubernetes Service (AKS)
51. Kubernetes deployment YAML
52. `Deployment`, `Service`, `Ingress`
53. ConfigMaps y Secrets en K8s
54. HPA (Horizontal Pod Autoscaler)
55. Helm charts para ASP.NET Core
56. AWS Elastic Beanstalk
57. AWS ECS (Elastic Container Service)
58. AWS EKS
59. Deployment strategies:
60. Rolling update
61. Blue-green deployment
62. Canary deployment
63. A/B testing deployment
64. Feature flags para deployment
65. `Microsoft.FeatureManagement`
66. Environment management (Dev, Staging, Production)
67. Environment variables por environment
68. Configuration per environment
69. Database migrations en deployment
70. Pre-deployment migrations
71. Post-deployment scripts
72. Zero-downtime deployments
73. Health check-based traffic switching
74. Graceful shutdown en deployment
75. Rollback strategy
76. Monitoring post-deployment
77. Deployment notifications (Slack, Teams, Email)
78. Deployment approval gates
79. Terraform para infraestructura (IaC)
80. Terraform para Azure resources
81. Pulumi como alternativa
82. ARM templates / Bicep (Azure)
83. CloudFormation (AWS)
84. SSL/TLS certificates
85. Let's Encrypt para certs
86. Azure Managed Certificates
87. Custom domains
88. DNS configuration
89. CDN configuration (Azure CDN, CloudFront)
90. WAF (Web Application Firewall)
91. DDoS protection
92. Monitoring post-deployment: Application Insights
93. Monitoring: Grafana + Prometheus
94. Alerting: thresholds y notifications
95. SLO/SLA definitions
96. Incident management
97. Post-mortem process
98. Documentation: runbooks
99. DevOps culture y practices
100. Best practices de CI/CD para ASP.NET Core

---

## MÓDULO 50: PERFORMANCE, ESCALABILIDAD Y ARQUITECTURA SENIOR

**Descripción:** Este módulo final cubre los temas que diferencian a un desarrollador senior: optimización de performance, escalabilidad horizontal y vertical, patrones de arquitectura avanzados, y decisiones técnicas a nivel de sistema. Aquí consolidas todo lo aprendido en habilidades de nivel arquitecto.

1. Performance vs Scalability: diferencias
2. Latency vs Throughput
3. Amdahl's Law y escalabilidad
4. Profiling: herramientas y técnicas
5. `dotnet-trace` para recolectar traces
6. `dotnet-counters` para métricas en tiempo real
7. `dotnet-dump` para memory dumps
8. Visual Studio Profiler
9. JetBrains dotTrace y dotMemory
10. BenchmarkDotNet: microbenchmarks
11. `[Benchmark]` attribute
12. Memory profiling: memory leaks detection
13. GC analysis: gen0, gen1, gen2 collections
14. Large Object Heap (LOH) considerations
15. `Span<T>` y `Memory<T>` para zero-allocation
16. `stackalloc` para stack allocation
17. `ArrayPool<T>` para buffer reuse
18. `ObjectPool<T>` para object reuse
19. String interpolation vs concatenation performance
20. `StringBuilder` pooling
21. Async performance: avoid sync-over-async
22. `ConfigureAwait(false)` en librerías
23. ValueTask vs Task: cuándo usar cada uno
24. Synchronous vs Asynchronous I/O
25. Database performance: query optimization
26. N+1 problem en EF Core y cómo resolverlo
27. `AsSplitQuery()` para múltiples includes
28. `AsNoTracking()` para queries de lectura
29. Compiled queries en EF Core
30. `DbContextPooling`
31. Database indexing strategies
32. Query plan analysis
33. Connection pooling
34. Dapper para queries de alto rendimiento
35. Caching strategies para performance
36. Multi-layer caching (L1: memory, L2: Redis)
37. Cache warming
38. Response compression (Gzip, Brotli)
39. Output caching para pages estáticos
40. CDN para assets estáticos
41. HTTP/2 y HTTP/3 benefits
42. Kestrel tuning
43. Kestrel limits: `MaxConcurrentConnections`
44. Request decompression
45. Keep-alive connections
46. Connection draining
47. Load balancing strategies
48. Round-robin, least connections, IP hash
49. Reverse proxy: Nginx tuning
50. Load testing: k6, Apache Bench, wrk
51. Stress testing
52. Chaos engineering
53. Scalability patterns:
54. Horizontal scaling (scale out)
55. Vertical scaling (scale up)
56. Auto-scaling en Azure/AWS
57. Stateless services para horizontal scaling
58. Session state: distributed (Redis)
59. Database read replicas
60. CQRS para read scalability
61. Event sourcing para write scalability
62. CQRS + Event Sourcing juntos
63. Eventual consistency: accepting and handling
64. Distributed transactions: Saga pattern
65. Compensating transactions
66. CAP theorem: Consistency, Availability, Partition tolerance
67. PACELC theorem
68. Database sharding
69. Sharding strategies (hash, range, geo)
70. Multi-tenancy: shared database
71. Multi-tenancy: database per tenant
72. Multi-tenancy: schema per tenant
73. Tenant resolution (header, subdomain, route)
74. Architecture decision records (ADR)
75. Technical debt management
76. Code review best practices
77. Refactoring strategies
78. Modular monolith architecture
79. Module communication patterns
80. Domain events entre modules
81. API design for long-term evolution
82. Backward compatibility strategies
83. Feature flags para safe rollout
84. A/B testing infrastructure
85. Observability: logs, metrics, traces (three pillars)
86. OpenTelemetry unified observability
87. Grafana dashboards para todo el sistema
88. SLO (Service Level Objectives)
89. Error budgets
90. Incident response process
91. Disaster recovery planning
92. Backup strategies
93. Multi-region deployment
94. Global distribution
95. Cost optimization en cloud
96. FinOps practices
97. Security hardening
98. Penetration testing concepts
99. Security audit checklist
100. Continuous learning: staying current as a senior developer

---

# RESUMEN DE NIVELES

| Nivel | Módulos | Descripción |
|---|---|---|
| **Fundamentos** | 1-10 | C#, .NET, HTML/CSS/JS, MVC, Razor, Forms, Layouts |
| **Intermedio Básico** | 11-20 | EF Core, LINQ, Migrations, DI, Middleware, Config, Logging, Errors, Filtros, Auth Cookies |
| **Intermedio** | 21-30 | Web API, REST, Swagger, JWT, Authorization, CORS, Versioning, Razor Pages, SignalR |
| **Intermedio-Avanzado** | 31-40 | Blazor Server/WASM/.NET 8, Minimal APIs, Caching, Background Services, Files, Health Checks, Rate Limiting, Output Cache, gRPC |
| **Avanzado** | 41-50 | Clean Architecture, CQRS, DDD, Microservices, Message Queues, GraphQL, Identity/OAuth, Testing, CI/CD, Performance/Senior |

**Total: 50 módulos × 100 temas = 5,000 temas**
