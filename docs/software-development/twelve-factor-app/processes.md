
# Processes (Concept)
## Description
Execute the app as one or more stateless processes


## Documentation
The app is executed in the execution environment as one or more processes.

In the simplest case, the code is a stand-alone script, the execution environment is a
developer’s local laptop with an installed language runtime, and the process is launched
via the command line (for example, python my_script.py). On the other end of the spectrum,
a production deploy of a sophisticated app may use many process types, instantiated into
zero or more running processes.

Twelve-factor processes are stateless and share-nothing. Any data that needs to persist
must be stored in a stateful backing service, typically a database.

The memory space or filesystem of the process can be used as a brief, single-transaction
cache. For example, downloading a large file, operating on it, and storing the results of
the operation in the database. The twelve-factor app never assumes that anything cached in
memory or on disk will be available on a future request or job – with many processes of
each type running, chances are high that a future request will be served by a different
process. Even when running only one process, a restart (triggered by code deploy, config
change, or the execution environment relocating the process to a different physical location)
will usually wipe out all local (e.g., memory and filesystem) state.

Asset packagers like django-assetpackager use the filesystem as a cache for compiled assets.
A twelve-factor app prefers to do this compiling during the build stage. Asset packagers
such as Jammit and the Rails asset pipeline can be configured to package assets during the
build stage.

Some web systems rely on “sticky sessions” – that is, caching user session data in memory
of the app’s process and expecting future requests from the same visitor to be routed to
the same process. Sticky sessions are a violation of twelve-factor and should never be used
or relied upon. Session state data is a good candidate for a datastore that offers
time-expiration, such as Memcached or Redis.
## Other Relations
| From | Name | To | Description |
|---|---|---|---|
| [Processes](../../software-development/twelve-factor-app/processes.md) | factor of | [12 Factor App](../../software-development/twelve-factor-app/twelve-factor-app.md) | execute the app as one or more stateless processes |

## Concept Map
![Concept Map for Twelve Factor Apps](../../software-development/twelve-factor-app/concept-view.png)

[Concept Map for Twelve Factor Apps](../../software-development/twelve-factor-app/concept-view.md)


## Navigation
[List of views in namespace](./views-in-namespace.md)

[List of all Views](../../views.md)


(generated by [Overarch](https://github.com/soulspace-org/overarch) with template docs/node.md.cmb)
