theme: New Story

# Offline Strategies

## React Native

^ Let's take a look at why offline matters for mobile apps and look at some strategies that will help you build robust and performant offline first mobile apps.

--- 

# Tim Whitacre

## Engineering Manager @ New Story Charity

> We pioneer solutions to end global homelessness.

### :sparkles: [@timwco](https://twitter.com/timwco)

### :sparkles: [@newstorycharity](https://twitter.com/newstorycharity)

---

# Why Offline First & Why Now?

* Connected & Powered to Disconnected & Battery
* Geography plays an important role
* Offline is simply a fact of life. :thumbsup:

--- 

# Problems

- Local Data Loss
- Offline is Bad :thumbsdown: (we treat it that way)
- Data Conflicts
- Diverse Data Types
- Others [^1]

[^1]: https://alistapart.com/article/offline-first

--- 

# Solutions

> Offline first requires a mix of UX and Development Strategies :fire:

... basically, don't skip the UX part

---

# How Do Offline Apps Work? 

![inline)](images/diagram.png)

--- 

# Offline Strategies (Tools)

- GraphQL
- Local Storage
- Redux Offline
- Realm
- AWS AppSync

--- 

# GraphQL

### Only get the data that we need. Less queries, less operations and quicker access to data.

![inline)](images/graphql.png)


#### [Image Credit](https://devopedia.org/graphql)

---

# Redux Offline

### Redux Offline allows us to store and "rehydrate" our state as needed. It gives us deep control over how our data is stored and managed.

![inline)](images/reduxoffline.png)


#### [Image Credit](https://hackernoon.com/introducing-redux-offline-offline-first-architecture-for-progressive-web-applications-and-react-68c5167ecfe0)

---

# Realm

> Realm Database is a fast, easy to use, and open source alternative to SQLite and Core Data.

* Allows us to define a schema
* Loads data on new threads
* Security FTW :tada:
* Realtime data updates

---

# Specific Solutions

- Local Data Loss (Realm)
- Offline is Bad (UX)
- Data Conflicts (Realm, GraphQL)
- Diverse Data Types (Realm, GraphQL)
