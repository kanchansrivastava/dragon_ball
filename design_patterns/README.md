## Design Pattern & their Usage

**Factory pattern**

- When the type of objects required cannot be anticipated beforehand.
- When multiple objects that share similar characteristics need to be created.
- When you want to generalize the object instantiation process, since the object set up is complex in nature.

**Constructor pattern**

- You can use it when you want to create multiple instances of the same template, since the instances can share methods but can still be different. 
- It can be useful in the Libraries and Plugins design.

**Singleton pattern**

- The Singleton pattern is mostly used in cases where we want a single object to coordinate actions across a system.
- Services can be singleton since they store the state, configuration, and provide access to resources. Therefore, it makes sense to have a single instance of a service in an application.
- Databases such as MongoDB utilize the Singleton pattern when it comes to database connections.
- Configurations are used if there is an object with a specific configuration, and we don’t need a new instance every time that configuration object is needed.

**Builder pattern**

- You can use this design pattern when building apps that require you to create complex objects. It can help you hide the construction process of building these objects.
- A good example would be a DOM, where we might need to create plenty of nodes and attributes. The construction process can get quite messy if we are building a complex DOM object. In cases like these, the Builder pattern can be used.

**Prototype pattern**

- To eliminate the overhead of initializing an object.
- When we want the system to be independent about how the products in it are created.
- When creating objects from a database whose values are copied to the cloned object.

**Abstract pattern**

- Applications requiring the reuse or sharing of objects.
- Applications with complex logic because they have multiple families of related objects that need to be used together.
- When we require object caching.
- When the object creation process is to be shielded from the client.