react-cloud
===========

Self-service web console exposing application capabilties such as messaging, caching, and monitoring, to quickly register and leverage such services.


## App Console
Register your application services and generate a unique app ID, that's it; the app ID automatically registers access to all internal cloud services. 

#### Active Apps
Lists all of your active applications and active versions. 
<p>
<a href="http://www.nextideapartners.com/site/images/git/apps.png"><img src="http://www.nextideapartners.com/site/images/git/apps.png" /></a>
<p>


## Messaging-as-a-Service
Generate real-time events from structured and unstructured sources; create follow-up actions, such as send an email, evict acache item, etc., when those events occur. Completely configurable from console, no programmatic overhead required.

#### Define an Event
Source an event from anywhere; example below demonstrates event sourcing using a simple database poller. Messenger will query the table indefinitely, converting each row into an event. 
<p>
<a href="http://www.nextideapartners.com/site/images/git/new-event.png"><img src="http://www.nextideapartners.com/site/images/git/new-event.png" /></a>
<p>

#### Create Event Subscription/Follow-up Actions
Subscribe to event and configure actions to perform when events are generated. Example below defines an action to selectively evict cache items for applications using the cache service, demonstrating seamless integration between cloud services.  
<p>
<a href="http://www.nextideapartners.com/site/images/git/action.png"><img src="http://www.nextideapartners.com/site/images/git/action.png" /></a>
<p>
