# To Do - 2025 Updates

Following the changes in the EDH rulings with WOTC taking over, the following cards and power levels have been added:
- (source)


## Add missing .favicon
- Probably get someone to make this - hatthew's face?

## Enable Dev Mode
- Add hidden toggle to enable developer mode and show debug settings within the app

## Refactor for better Mobile Support
- Need to support smaller screen sizes, particualrly on the multi-line input text box that will get clipped on widths smaller than average

## Dark Mode Support
- Add Dark Mode button for colour swapping and not going blind

## Archidekt API Changes

In addition to that, the ArchiDekt API has been changes and no longer returns data on the old GET endpoints - we will need to refactor these/move to the suggested react library to ensure compatibility.

Sample URL: https://archidekt.com/api/decks/12814764/

- Using this without the CORS Proxy does seem to work, the plane is blocking our normal CORS proxy site
- Consider asking Eli to add a pod to the cluster that acts as a HTTp Listener/worker to forward requests

** FOR NOW **
- Let's add at toggle to enable/disable CORS proxy in the UI?

## Add Better Support for Deck URLs
- Include support for URLs that are direct API URLs, currently only supporting consumer-facing URLs