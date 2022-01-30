########
Observer
########

Observer is used for filtering and handling different events. It is part of an internal API with some public methods and it is not recommended to use methods not listed here.

In `aiogram` framework observer is available in two variants:

- `EventObserver <#eventobserver>`__
- `TelegramEventObserver <#telegrameventobserver>`__


EventObserver
=============

.. autoclass:: aiogram.dispatcher.event.event.EventObserver
    :members: register, trigger, __call__
    :member-order: bysource


TelegramEventObserver
=====================

.. autoclass:: aiogram.dispatcher.event.telegram.TelegramEventObserver
    :members: register, trigger, __call__, bind_filter, middleware, outer_middleware
    :member-order: bysource
