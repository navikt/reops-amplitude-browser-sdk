# Filer for å benytte amplitude-proxy med Browser SDK.

For å legge til Amplitude-sporing med browser-sdk trenger du å kjøre amplitudeBrowser.js-scriptet på klienten.

Scriptet er modifisert til å sende data til vår proxy for vasking før dataene sendes til Amplitude. 

Vi minner om at data ikke skal sendes direkte til amplitude, men alltid gjennom en proxy. 

[Her finner du NAVs amplitudeBrowser.js-script](https://cdn.nav.no/team-researchops/amplitudeNavBrowserSdk.js)
