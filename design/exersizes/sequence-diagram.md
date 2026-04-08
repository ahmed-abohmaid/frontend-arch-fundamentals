# Real-Time Order Status Sequence

## Description

When a customer places an order, the web app makes a request to the Core API which creates the order and returns a channel id. The web app then uses this channel ID to subscribe to the web sockets server, which emits real-time events when the order status changes. If the connection with the web socket server drops at any point, the web app will start polling Core API with the latest order status.

## My Solution

https://www.tldraw.com/f/pXcJN8-XEcmIh55Qse9tY?d=v-288.277.2652.1595.page

---

![sequence-diagram.png](images\sequence-diagram.png)
