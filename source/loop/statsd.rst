======
Statsd
======

Loop-Server have got a number of Statsd counters and timers that can
help monitor what's going on in near real-time.

+-------------------------------------------------------+----------+------------------------------------------------------------+
| Name                                                  | Type     | Description                                                |
+=======================================================+==========+============================================================+
| ``loop.activated-users``                              | counter  | New Hawk Session created for a user.                       |
+-------------------------------------------------------+----------+------------------------------------------------------------+
| ``loop.call-urls``                                    | counter  | New call-url creation.                                     |
+-------------------------------------------------------+----------+------------------------------------------------------------+
| ``loop.simplepush.call``                              | counter  | Calls made to a SimplePush URL.                            |
+-------------------------------------------------------+----------+------------------------------------------------------------+
| ``loop.simplepush.call.(success|failures)``           | counter  | SimplePush calls success and failures.                     |
+-------------------------------------------------------+----------+------------------------------------------------------------+
| ``loop.simplepush.call.{reason}``                     | counter  | Calls made to a SimplePush URL for a given reason.         |
+-------------------------------------------------------+----------+------------------------------------------------------------+
| ``loop.simplepush.call.{reason}.(success|failures)``  | counter  | Calls success and failures on SP urls for a given reason.  |
+-------------------------------------------------------+----------+------------------------------------------------------------+
| ``loop.aws.write``                                    | timer    | AWS S3 roomContext write calls.                            |
+-------------------------------------------------------+----------+------------------------------------------------------------+
| ``loop.aws.read``                                     | timer    | AWS S3 roomContext read calls.                             |
+-------------------------------------------------------+----------+------------------------------------------------------------+
| ``loop.aws.remove``                                   | timer    | AWS S3 roomContext deletion calls.                         |
+-------------------------------------------------------+----------+------------------------------------------------------------+
| ``loop.filesystem.write``                             | timer    | Filesystem roomContext write calls.                        |
+-------------------------------------------------------+----------+------------------------------------------------------------+
| ``loop.filesystem.read``                              | timer    | Filesystem roomContext read calls.                         |
+-------------------------------------------------------+----------+------------------------------------------------------------+
| ``loop.filesystem.remove``                            | timer    | Filesystem roomContext deletion calls.                     |
+-------------------------------------------------------+----------+------------------------------------------------------------+
| ``loop.tokbox.createSession``                         | timer    | TokBox createSession calls.                                |
+-------------------------------------------------------+----------+------------------------------------------------------------+
