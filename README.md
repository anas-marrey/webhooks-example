# webhooks-example

Example on Webhooks.

Setup
---------------------

Simply give **install.sh** script execute permission, then run the script.

```
$ chmod +x install.sh
$ source ./install.sh
$ composer install
```

Create Event command
--------------------------

 This Command Registers a webhook for the given event-name and the callback-url


```
$ webhooks create <event-name> <callback-url>

```
  
 
 
Dispatch Event command
--------------------------

 This Command Dispatches an event. in case of Failure it will reschedule the event for later processing. 
 
```
$ webhooks dispatch <event-name> <message>

```
 