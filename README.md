![Distillery](https://distillery.com/content/uploads/2018/07/logo.svg)

# Distillery growing course

- [Distillery growing course](#distillery-growing-course)
- [Frontend (General)](#frontend-general)
  - [Prerequisites](#prerequisites)
  - [Network (Basic)](#network-basic)
  - [Semantic HTML (Basic)](#semantic-html-basic)
  - [CSS (Basic)](#css-basic)
  - [HTML / CSS tools (Basic)](#html--css-tools-basic)
  - [CSS pre- & post- processors](#css-pre---post--processors)
  - [CSS Architecture](#css-architecture)
  - [Package managers](#package-managers)
  - [CSS Frameworks](#css-frameworks)
  - [Build tools](#build-tools)
  - [JavaScript (ES2018)](#javascript-es2018)
  - [JS Networking](#js-networking)
  - [TypeScript](#typescript)
  - [RxJS](#rxjs)
  - [MobX](#mobx)
- [Frontend - Angular](#frontend---angular)
  - [Angular](#angular)
- [Frontend - React](#frontend---react)
- [Frontend - Vue](#frontend---vue)
- [Mobile - React Native](#mobile---react-native)
  - [React-Native cross-platform [Basic]](#react-native-cross-platform-basic)
  - [React-Native [Intermediate]](#react-native-intermediate)
  - [React-Native [Advanced]](#react-native-advanced)

# Frontend (General)

## Prerequisites

Basic development principles, general for any development path

- Data structures and algorithms
- Design patterns
- SOLID, KISS, YAGNI
- Licenses
- Semantic versioning
- Character encodings

## Network (Basic)

How modern networks work from developers POV

- IP
- TCP
- UDP
- HTTP
- HTTP/2
- QUIC
- TLS, SSL
- DNS
- NTP

## Semantic HTML (Basic)

Basic HTML/Web

- What is "semantics" and why do we need it?
- Document structure
- Head and metadata
- Hyperlinks. A fundament of the Web.
- Block and inline elements
- Headers
- Paragraphs
- Text: emphasis and importance
- Whitespaces in HTML
- Special characters
- Lists
- Nested lists
- Tables
- Multimedia and embedding
- Images
- Video and audio content
- Vector graphics
- Responsive images
- Objects and IFrames
- Forms
  - Label
  - Input (+types)
  - Select
  - Textarea
  - Validation
  - Button

## CSS (Basic)

- Basic syntax
- Selectors
  - Element selectors
  - Class selectors
  - ID selectors
  - Universal selector \*
  - Attribute selectors
  - Combinators and selector list
  - Selector specificity
- Pseudo classes and pseudo-elements
- Layout
  - Floats
  - Positioning
  - Display
  - Box model
  - CSS Grid
  - Flexbox
- CSS values and units
- Cascade and inheritance
- Fonts
- Styling font and text layout
- Styling lists
- Styling links

## HTML / CSS tools (Basic)

- Chrome inspector
- Firefox inspector
- Safari inspector
- HTML validation
- CSS validation

## CSS pre- & post- processors

- SCSS
  - Import - fragments, nested imports, index
  - Mixins, @extend
  - SassScript
- PostCSS
  - Autoprefixer
  - CSSNext
  - PreCSS
  - Stylelint

## CSS Architecture

- Isolation
- Specificity wars
- Garbage collection
- BEM

## Package managers

- Licenses (ref to **Prerequisites**)
- Semantic versioning (ref to **Prerequisites**)
- NPM
  - Dependencies, dev-devependencies
  - Package scope, access level, visibility
  - Publishing
  - Scripts
  - Audit & Security
- Yarn

## CSS Frameworks

- Bootstrap
- Materialize CSS
- Bulma
- Semantic UI

## Build tools

- Task runners
  - NPM scripts
  - Gulp
- Bundlers
  - Webpack
  - Parcel
  - Rollup
- Linters & formaters
  - Prettier
  - ESLint
  - Stylelint
  - TSLint (will be deprecvtaed soon)

## JavaScript (ES2018)

- Grammar and types
- Control flow & error handling
- Loops & iteration
- Functions
  - Arrow functions
- Closures
- Expressions & operators
- Numbers & dates
- Text formatting
- Resular expressions
- Arrays (indexed collections)
- Map, WeakMap, Set (keyed collections)
- Objects, prototypical inheritance
- Promises
  - Async/await syntax
- Iterators & generators
- Meta-programming
  - Handlers & traps
  - Proxy
  - Revocable proxy
  - Reflection
- Strict mode
- Template literals
- Symbols
- Spread operator, rest parameters
- Shared memory, ArrayBuffer, TypedObject
- Eventloop

## JS Networking

- XHR
  - CORS
- WebSockets

## TypeScript

- Basic types
- Variable declarations
- Interfaces
- Classes
- Functions
- Generics
- Enums
- Type inference
- Type compatibility
- Advanced types
  - Intersection of types
  - Union types
  - Type guards
  - String literal types
  - Index types
  - Mapped types
  - Conditional types
    - Exclude<T, U>
    - Extract<T, U>
    - NonNullable<T>
    - ReturnType<T>
    - InstanceType<T>
- Symbols
- Iterators & generators
- Modules
  - Module resolution
- Namespaces
- Declaration merging
- JSX / TSX
- Decorators
- Mixins
- Publishing

## RxJS

- Observables
  - Hot
  - Cold
- Operators
  - Combination
  - Conditional
  - Creation
  - Error handling
  - Multicasting
  - Filtering
  - Transformation
  - Utility
- Subjects
  - AsyncSubject
  - BehaviorSubject
  - ReplaySubject
  - Subject

## MobX

- Concepts and Principles
- Decorators
- Observable
  - Objects
  - Arrays
  - Maps
  - Boxed Values
- Observers
- Reactions
  - Autorun
  - When
  - Reaction
- Actions
  - Synchronous
  - Asynchronous
- Computed Values
- Mobx React Devtools

![Angular](https://upload.wikimedia.org/wikipedia/commons/thumb/c/cf/Angular_full_color_logo.svg/250px-Angular_full_color_logo.svg.png)

# Frontend - Angular

## Angular

- CLI - Command line interface
- Schematics
- Modules
  - JS modules vs Angular modules
  - Feature modules
    - Domain feature modules
    - Routed feature modules
    - Routing modules
    - Service feature modules
    - Widget feature modules
  - Entry components
  - Declarations
  - Providers
  - Lazy loading feature modules
  - Sharing modules
- Components
- Services and DI
  - Hierarchical dependency injectors
  - DI providers
  - Singleton services
- Templates
  - Template syntax
  - Lifecycle hooks
  - User input
  - Component interaction
  - Component styles
  - Angular components (Custom elements)
  - Dynamic components
    - Factories
    - Outlets
- Attribute directives
- Structural directives
- Pipes
- Forms
  - Reactive forms
  - Dynamic forms
  - Template-driven forms
  - Validation
- Observables in Angular
- HTTPClient
- Routing & Navigation
- Animations
- Bootstraping
- Internalization
- Angular libraries
- Server-side rendering
- Service workers & PWA
- Security
  - XSS
  - CSRF
  - XSSI
- AOT (Ahead of time) compilation
- Testing

![React](https://miro.medium.com/max/480/1*To2H39eauxaeYxYMtV1afQ.png)

# Frontend - React

- Project Scaffolding
  - create-react-app
  - nextjs
- React Developer Tools
- JSX
- Components
  - State and Props
  - Lifecycle
- Events
  - Handling Events
  - Syntetic Events
- Forms
  - Controlled and Uncontrolled Components
  - Forms Validation
- Refs
- Rendering
  - Conditional Rendering
  - Preventing from Rendering
- Higher Order Components
- Context API
- React Hooks
  - State Hook
  - Effect Hook
  - Rules of Hooks
- Portals
- Accessibility
- Animations
- Internationalization
- Optimizing Performance
- List and Keys
- Static Type Checking
- SSR - Server Side Rendering
  - nextJS
- Reconciliation
- Fiber API
- Scheduling
- Testing
- Service Workers & PWA
- Security
  - XSS
  - CSRF
  - XSS

# Frontend - Vue

# Mobile - React Native

## React-Native cross-platform [Basic]

- Project scaffolding
  - CRNA (create-react-native-app)
  - Expo SDK
  - Adding TypeScript to CRNA app
- Basic React usage (see [Frontend - React](#frontend---react))
- React Context API
- Styles & Stylesheet
- Flexbox layout
- Networking
  - XHR
  - Fetch API
  - WebSocket support
- Storages
  - AsyncStorage
- Components
  - Text
  - Text input
  - Button
  - Touchables
  - Gesture responder
  - ScrollView
  - List views
    - Flat list
    - Section list
    - Virtualized list
    - Swipeable list view
  - Image
    - Static resources
    - Network resources
    - URI Data images
    - Cache control (iOs)
    - Background image (via Nesting)
  - Picker
  - Slider
  - Switch
  - ActivityIndicator
  - Alert
  - Animated
  - CameraRoll
  - Clipboard
  - Dimensions
  - KeyboardAvoidingView
  - Linking
  - Modal
  - PixelRatio
  - RefreshControl
  - StatusBar
  - WebView
- Animations
- Accessibility
- Navigation
- Timers
- Running
  - on iOS simulator
  - on iOS device
  - on Android simulator
  - on Android device
- Debugging
- Performance profiling
- App publishing

## React-Native [Intermediate]

- iOs-specific components
  - ActionSheetIOS
  - AlertIOS
  - DatePickerIOS
  - ImagePickerIOS
  - NavigatorIOS
  - ProgressViewIOS
  - PushNotificationIOS
  - SegmentedContolIOS
  - TabBarIOS
- Android-specific components
  - BackHandler
  - DatePickerAndroid
  - DrawerLayoutAndroid
  - PermissionsAndroid
  - ProgressBarAndroid
  - TimePickerAndroid
  - ToastAndroid
  - ToolbarAndroid
  - ViewPagerAndroid
- Expo SDK (most used components)
  - AppAuth
  - AppLoading
  - Asset
  - Audio
  - AuthSession
  - AV
  - BackgroundFetch
  - Calendar
  - Camera
  - Contacts
  - DocumentPicker
  - FileSystem
  - Font
  - GestureHandler
  - ImagePicker
  - IntentLauncherAndroid
  - KeepAwake
  - LinearGradient
  - Linking
  - Location
  - MapView
  - MediaLibrary
  - Notifications
  - Payments
  - Permissions
  - SecureStore
  - Sensors
  - SMS
  - SplashScreen
  - Svg
  - TaskManager
  - Updates
  - Video
  - WebBrowser

## React-Native [Advanced]

- Integration with Existing Apps
- Creating native modules
  - iOS
  - Android
- Communication between native and React Native
- Using Jest for JS test
- Using Detox for iOs
- Using Appium
- Working with stack trace

# .Net

## CLR

- Assemblies
- CLR
- IL
- The Common Type System (CTS)
- The Framework Class Library (FCL)
- The Common Language Specification (CLS)

## Designing Types

- Fundamentals
  - System.Object <a title="CLR via C# - 2012, p. 91" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>
  - Types casting <a title="CLR via C# - 2012, p. 93" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>
  - Namespaces and assemblies <a title="CLR via C# - 2012, p. 97" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>

- Reference and ValueTypes
  - Reference Types and Value Types <a title="CLR via C# - 2012, p. 118" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>
  - Boxing and Unboxing <a title="CLR via C# - 2012, p. 124" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>, <a title="C# 7.0 in a Nutshell The Definitive Reference, p. 106" href="https://www.amazon.com/C-7-0-Nutshell-Definitive-Reference/dp/1491987650/ref=sr_1_2?dchild=1&keywords=Joseph+Albahari+%26+Ben+Albahari+-+C%23+7.0+-+Pocket+Reference&qid=1605618350&s=digital-text&sr=1-2">[?]</a>
  - Object HashCode <a title="CLR via C# - 2012, p. 142" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>
  - Dynamic <a title="CLR via C# - 2012, p. 144" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>

- Types and Members kinds
  - Visibility <a title="CLR via C# - 2012, p. 154" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>
  - Accessability <a title="CLR via C# - 2012, p. 156" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>
  - Static <a title="CLR via C# - 2012, p. 158" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>
  - Partial classes <a title="CLR via C# - 2012, p. 159" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>
  - Polymorphism <a title="CLR via C# - 2012, p. 160" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>, <a title="C# 7.0 in a Nutshell The Definitive Reference, p. 97" href="https://www.amazon.com/C-7-0-Nutshell-Definitive-Reference/dp/1491987650/ref=sr_1_2?dchild=1&keywords=Joseph+Albahari+%26+Ben+Albahari+-+C%23+7.0+-+Pocket+Reference&qid=1605618350&s=digital-text&sr=1-2">[?]</a>
    - Virtual Methods <a title="CLR via C# - 2012, p. 162" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>, <a title="C# 7.0 in a Nutshell The Definitive Reference, p. 100" href="https://www.amazon.com/C-7-0-Nutshell-Definitive-Reference/dp/1491987650/ref=sr_1_2?dchild=1&keywords=Joseph+Albahari+%26+Ben+Albahari+-+C%23+7.0+-+Pocket+Reference&qid=1605618350&s=digital-text&sr=1-2">[?]</a>
    - Overriding <a title="C# 7.0 in a Nutshell The Definitive Reference, p. 102" href="https://www.amazon.com/C-7-0-Nutshell-Definitive-Reference/dp/1491987650/ref=sr_1_2?dchild=1&keywords=Joseph+Albahari+%26+Ben+Albahari+-+C%23+7.0+-+Pocket+Reference&qid=1605618350&s=digital-text&sr=1-2">[?]</a>
    - Overloading <a title="C# 7.0 in a Nutshell The Definitive Reference, p. 105" href="https://www.amazon.com/C-7-0-Nutshell-Definitive-Reference/dp/1491987650/ref=sr_1_2?dchild=1&keywords=Joseph+Albahari+%26+Ben+Albahari+-+C%23+7.0+-+Pocket+Reference&qid=1605618350&s=digital-text&sr=1-2">[?]</a>

- Constants and Fields <a title="CLR via C# - 2012, p. 175" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>

- Methods  <a title="CLR via C# - 2012, p. 181" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>
  - Instance Constructors and Classes (Reference Typse) <a title="CLR via C# - 2012, p. 181" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>
  - Instance Constructors and Structures (Value Types) <a title="CLR via C# - 2012, p. 184" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>
  - Type constructors <a title="CLR via C# - 2012, p. 187" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>, <a title="C# 7.0 in a Nutshell The Definitive Reference, p. 82" href="https://www.amazon.com/C-7-0-Nutshell-Definitive-Reference/dp/1491987650/ref=sr_1_2?dchild=1&keywords=Joseph+Albahari+%26+Ben+Albahari+-+C%23+7.0+-+Pocket+Reference&qid=1605618350&s=digital-text&sr=1-2">[?]</a>
    - Type Constructor Performance
  - Extensions methods
  - Partial Methods <a title="CLR via C# - 2012, p. 204" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>, <a title="CLR via C# - 2012, p. 94" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>
  - Finalizers <a title="C# 7.0 in a Nutshell The Definitive Reference, p. 94" href="https://www.amazon.com/C-7-0-Nutshell-Definitive-Reference/dp/1491987650/ref=sr_1_2?dchild=1&keywords=Joseph+Albahari+%26+Ben+Albahari+-+C%23+7.0+-+Pocket+Reference&qid=1605618350&s=digital-text&sr=1-2">[?]</a>

- Parameters <a title="CLR via C# - 2012, p. p. 209" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>
  - Optional and Named <a title="CLR via C# - 2012, p. 209" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>
  - Implicitly Typed Local Variable <a title="CLR via C# - 2012, p. 212" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>
  - Passging parameter by Reference <a title="CLR via C# - 2012, p. 214" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>
  - Passing a Variable Number of Arguments <a title="CLR via C# - 2012, p. 220" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>
  - Parameter and Return Type Guidelines <a title="CLR via C# - 2012, p. 223" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>

- Properties <a title="CLR via C# - 2012, p. 227" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>, <a title="C# 7.0 in a Nutshell The Definitive Reference, p. 87" href="https://www.amazon.com/C-7-0-Nutshell-Definitive-Reference/dp/1491987650/ref=sr_1_2?dchild=1&keywords=Joseph+Albahari+%26+Ben+Albahari+-+C%23+7.0+-+Pocket+Reference&qid=1605618350&s=digital-text&sr=1-2">[?]</a>
  - The performance of calling Porperty Accessor Methods <a title="CLR via C# - 2012, p. 247" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>

- Generics <a title="CLR via C# - 2012, p. 265" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>, <a title="C# 7.0 in a Nutshell The Definitive Reference, p. 121" href="https://www.amazon.com/C-7-0-Nutshell-Definitive-Reference/dp/1491987650/ref=sr_1_2?dchild=1&keywords=Joseph+Albahari+%26+Ben+Albahari+-+C%23+7.0+-+Pocket+Reference&qid=1605618350&s=digital-text&sr=1-2">[?]</a>

## Essential Types

- Chars, Strings and Working with Text. <a title="CLR via C# - 2012, p. 317" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>, <a title="CLR via C# - 2012, p. 39" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>
  - System.String  <a title="CLR via C# - 2012, p. 320" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>
  - StringBuilder  <a title="CLR via C# - 2012, p. 336" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>

## Core Facilities

- Exceptions  <a title="CLR via C# - 2012, p. 451" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>, <a title="C# 7.0 in a Nutshell The Definitive Reference, p. 158" href="https://www.amazon.com/C-7-0-Nutshell-Definitive-Reference/dp/1491987650/ref=sr_1_2?dchild=1&keywords=Joseph+Albahari+%26+Ben+Albahari+-+C%23+7.0+-+Pocket+Reference&qid=1605618350&s=digital-text&sr=1-2">[?]</a>
  - Exceptions performance <a title="CLR via C# - 2012,p. 492" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>
  - Guidelines <a title="CLR via C# - 2012,p. 478" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>
- GC <a title="CLR via C# - 2012, p. 507" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>, <a title="C# 7.0 in a Nutshell The Definitive Reference, p. 519" href="https://www.amazon.com/C-7-0-Nutshell-Definitive-Reference/dp/1491987650/ref=sr_1_2?dchild=1&keywords=Joseph+Albahari+%26+Ben+Albahari+-+C%23+7.0+-+Pocket+Reference&qid=1605618350&s=digital-text&sr=1-2">[?]</a>
- Memory <a title="C# 7.0 in a Nutshell The Definitive Reference, p. 530" href="https://www.amazon.com/C-7-0-Nutshell-Definitive-Reference/dp/1491987650/ref=sr_1_2?dchild=1&keywords=Joseph+Albahari+%26+Ben+Albahari+-+C%23+7.0+-+Pocket+Reference&qid=1605618350&s=digital-text&sr=1-2">[?]</a> , <a title="CLR via C# - 2012, p. 505" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>

## Threading

- Threading <a title="CLR via C# - 2012, p. 669" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>, <a title="C# 7.0 in a Nutshell The Definitive Reference, p. 560, 870" href="https://www.amazon.com/C-7-0-Nutshell-Definitive-Reference/dp/1491987650/ref=sr_1_2?dchild=1&keywords=Joseph+Albahari+%26+Ben+Albahari+-+C%23+7.0+-+Pocket+Reference&qid=1605618350&s=digital-text&sr=1-2">[?]</a>
- CLR Thread and Windows Threads
  - CLR's Thread Pool <a title="CLR via C# - 2012, p. 692" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>
  - Execution Contexts <a title="CLR via C# - 2012, p. 694" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>
  - Tasks  <a title="CLR via C# - 2012, p. 700" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>, <a title="C# 7.0 in a Nutshell The Definitive Reference, p. 577" href="https://www.amazon.com/C-7-0-Nutshell-Definitive-Reference/dp/1491987650/ref=sr_1_2?dchild=1&keywords=Joseph+Albahari+%26+Ben+Albahari+-+C%23+7.0+-+Pocket+Reference&qid=1605618350&s=digital-text&sr=1-2">[?]</a>
  - Primitive Thread Synchronization Constructs <a title="CLR via C# - 2012, p. 757" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>
    - Mutex <a title="CLR via C# - 2012, p. 785" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>, <a title="C# 7.0 in a Nutshell The Definitive Reference, p. 877" href="https://www.amazon.com/C-7-0-Nutshell-Definitive-Reference/dp/1491987650/ref=sr_1_2?dchild=1&keywords=Joseph+Albahari+%26+Ben+Albahari+-+C%23+7.0+-+Pocket+Reference&qid=1605618350&s=digital-text&sr=1-2">[?]</a>
    - Interlocked <a title="CLR via C# - 2012, p. 768" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>
  - Hybrid Thread Synchronization Constructs
    - ManualRestEventSlim, SemaphoreSlim <a title="CLR via C# - 2012, p. 794" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>
    - Monitor <a title="CLR via C# - 2012, p. 794" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>
    - ReaderWriterLockSlim <a title="CLR via C# - 2012, p. 800" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>, <a title="C# 7.0 in a Nutshell The Definitive Reference, p. 885" href="https://www.amazon.com/C-7-0-Nutshell-Definitive-Reference/dp/1491987650/ref=sr_1_2?dchild=1&keywords=Joseph+Albahari+%26+Ben+Albahari+-+C%23+7.0+-+Pocket+Reference&qid=1605618350&s=digital-text&sr=1-2">[?]</a>

## Best Practise

- Extensions methods <a title="CLR via C# - 2012, p. 200" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>
- Partial methods <a title="CLR via C# - 2012, p. 207" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>
- Optional and named parameters <a title="CLR via C# - 2012, p. 209" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>
- Parameter and return type <a title="CLR via C# - 2012, p. 223" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>
- Exceptions <a title="CLR via C# - 2012, p. 478" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>
- Design: Base Class or Interface? <a title="CLR via C# - 2012, p. 312" href="https://www.amazon.com/gp/product/B00JDMQJKQ/ref=dbs_a_def_rwt_hsch_vapi_tkin_p1_i0">[?]</a>, <a title="C# 7.0 in a Nutshell The Definitive Reference, p. 117" href="https://www.amazon.com/C-7-0-Nutshell-Definitive-Reference/dp/1491987650/ref=sr_1_2?dchild=1&keywords=Joseph+Albahari+%26+Ben+Albahari+-+C%23+7.0+-+Pocket+Reference&qid=1605618350&s=digital-text&sr=1-2">[?]</a>

`*` Keep in mind there is newer version of <a title="C# 7.0 in a Nutshell The Definitive Reference" href="https://www.amazon.com/C-7-0-Nutshell-Definitive-Reference/dp/1491987650/ref=sr_1_2?dchild=1&keywords=Joseph+Albahari+%26+Ben+Albahari+-+C%23+7.0+-+Pocket+Reference&qid=1605618350&s=digital-text&sr=1-2">[?]</a>, probably for other books newer versions are also available. Versions used in this article were chosen because they are widely available.

- Richter J. - CLR via C# - 2012
- C# 7.0 in a Nutshell: The Definitive Reference, 2017, first Edition
