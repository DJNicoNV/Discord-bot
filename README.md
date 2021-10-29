# Discord-bot
need help fixing this. getting an error that read as follows --
Ignoring exception in on_message
Traceback (most recent call last):
  File "/opt/virtualenvs/python3/lib/python3.8/site-packages/discord/client.py", line 343, in _run_event
    await coro(*args, **kwargs)
  File "main.py", line 59, in on_message
    options = options + db["encouragements"]
TypeError: can only concatenate list (not "ObservedList") to list
