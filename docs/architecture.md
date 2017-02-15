# Architecture

## Loose thoughts

- every widget is an independent small application
- widgets can publish and subscribe events
- widgets' configuration in stored in internal, file based, database and deployable within war
- widget's catalog is stored in git repository
- widget can be extended via extenstions mechanism
- permissions mechanism controls displaying whole widget in application, as well as can controls internals of widgets
- application structure must be visually edittable in any stage of application lifecycle
- application must be ready to move entirely to IDE tool (like Intellij Idea) and back to Core Web, if needed
- all entitlements must be managable via Core Web
- all backend API (both platform bulit-in and customer provided) must be accessible via Core Web
- i18n is a must
- application structure is stored in internal, file based, database but not deployed in war (in oppposite to widgets' conkfiguration)