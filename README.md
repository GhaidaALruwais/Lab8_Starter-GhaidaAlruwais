# Lab8-Starter-Ghaida Alruwais
## Team 
Ghaida Alruwais

## Graceful Degradation and Service Workers
Service workers are a perfect example of graceful degradation in modern web applications. While the app starts with full functionality when online, service workers allow it to gracefully degrade when network connectivity is lost. Instead of completely failing, the app continues to work by serving cached content from the service worker. This demonstrates graceful degradation because:
1. The app starts with full functionality (fresh data, live updates)
2. When network is unavailable, it degrades gracefully to cached content
3. Core functionality remains available even in degraded state
4. When network returns, it can seamlessly upgrade back to full functionality

This approach ensures that users always have access to the application's core features, even if some advanced functionality is temporarily unavailable due to network conditions.
<br>
[pages link](https://ghaidaalruwais.github.io/Lab8_Starter-GhaidaAlruwais/)
![PWA Screenshot](pwa.png)



