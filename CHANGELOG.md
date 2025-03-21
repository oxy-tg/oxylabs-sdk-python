# Changelog

## 2.0.0
- SERP and Ecommerce source split has been removed. New common modules have been created: API, Client and Response.
- Support for new sources has been added: google_maps, google_lens, kroger, kroger_product, kroger_search, youtube_transcript.
- Added browser_instructions parameter for universal source.
- Docs update.

## 1.0.7
- Add an SDK version identifier to all requests.

## 1.0.6

- Security updates in 3rd party libraries.
- Docs update.

## 1.0.5

- Cleaned up tests from obsolete credentials.

## 1.0.4

- Security updates in 3rd party libraries.

## 1.0.3

- Updated import paths to resolve module not found errors.
- Scraper methods now accept direct parameters and include a response object for easier access to results and metadata.
- Replaced print statements with the logging module for better error handling.
- Introduced AsyncClient, RealtimeClient, and ProxyClient to support all sources, providing a more organized structure.

## 1.0.2

- Fixed function and class naming.
- Added request timeout in proxy.
- Removed Yandex and Baidu sources from SERP.

## 1.0.1

- Fixed issue with uploaded package.

## 1.0.0

- Initial release of Oxylabs SDK.
- Scraper APIs:
  - SERP
  - Ecommerce
- Integration methods:
  - Proxy
  - Push-Pull
  - Realtime
