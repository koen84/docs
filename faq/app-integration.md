# 📲 App Integration

## I just want an endpoint, where can I get one?

## How does the Pocket Dashboard work?

The Pocket Dashboard is tasked with connecting to the Pocket Network through PocketJS on your behalf—essentially doing the integration work for you. The only thing that changes here is the layer of abstraction between you, the developer, and the nodes. You are still ultimately being served by a decentralized network of thousands of nodes.

## Is there a more "decentralized" solution?

Yes! You can integrate with PocketJS directly, which would be the most censorship-resistant way to connect to our network of full nodes. All of the functionality we built into the Pocket Dashboard, including "load-balanced" endpoints, are 100% reproducible using only PocketJS. In fact, we anticipate competing dashboards to emerge. Get started with PocketJS at the link below:

## What does it mean for an endpoint to be "load-balanced"?

This means that there's more than one Application behind your endpoint, where an Application is defined as the account staking into the network for the purpose of submitting relay requests. For each request you need to submit, one of these app stakes gets chosen pseudorandomly and is used to make the request to the network. We have several algorithms in place to cherry-pick the best-performing app stakes for each session, based on the nodes they've been matched with, and ensure the best QoS.

## What can I do if I exceed my allotted requests?

If you ever exceed the amount of daily \(or per-session\) amount of requests, contact the sales team or jump into our Discord to let us know; we'll work something out!

