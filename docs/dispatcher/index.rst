===============
Handling events
===============

*aiogram* includes Dispatcher mechanism.
Dispatcher is needed for handling incoming updates from Telegram.

With dispatcher you can:

- Handle incoming updates;
- Filter incoming events before they will be processed by a specific handler;
- Modify event and related data in middlewares;
- Separate bot functionality between different handlers, modules and packages.

Dispatcher is separated into two entities - Router and Dispatcher.
Dispatcher is a subclass of Router and should always be a root router.

.. toctree::

    observer
    router
    dispatcher
    class_based_handlers/index
    filters/index
    middlewares
    finite_state_machine/index
