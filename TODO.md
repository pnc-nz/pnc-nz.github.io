# To Do - 2025 Updates

Following the changes in the EDH rulings with WOTC taking over, the following cards and power levels have been added:
- (source)


## Archidekt API Changes

In addition to that, the ArchiDekt API has been changes and no longer returns data on the old GET endpoints - we will need to refactor these/move to the suggested react library to ensure compatibility.

Sample URL: https://archidekt.com/api/decks/12814764/

- Using this without the CORS Proxy does seem to work, the plane is blocking our normal CORS proxy site
- Consider asking Eli to add a pod to the cluster that acts as a HTTp Listener/worker to forward requests

