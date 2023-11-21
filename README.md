# 事前確認
1. Repositoryの整理 
```
rm -rf repository/*-*-*-*-*
```

2. settings.xmlの初期化

3. Anypoint Studioの最適化
```/Applications/AnypointStudio.app/Contents/Eclipse/AnypointStudio.ini```

```
// 最大Heapを調整
13c13
< -Xmx6000m
---
> -Xmx1024m
```


# Production Ready Development Practice
## Day1

## Common memo

### Information
* Organization
  * orgid : 16519426-0a08-4492-aa32-f1a70eb20e0f
  * clientid : 8a5328dced224cfb8ea193c9806d8227
  * clientsecret : e996F242FBe64c3f93d993eBBCf7F9dd

* ConnectedApps
  * Exchange Viewer
    * TBU
    * TBU
  * Exchange Contributor
    * TBU
    * TBU
  * CH Deployment
    * TBU
    * TBU

* API key
  * prod : 19120724
  * test : TBU
  * dev : TBU


### Tested version

```
Page numbers refer to the DEX6601 - Exercise Guide [Oct 23, 2023]

*  Page #5 [Product, component, and tool inventory]
This table must be updated with the following versions:
- Studio 7.16.0
- Mule Runtime - 4.5.0
- Mule maven plugin 4.0.0
- Exchange Mule Maven Plugin - 0.0.23
- MUnit and MUnit Maven Plugin - 3.0.0
- APIKit - 1.9.1
- HTTP - 1.8.0
- Secure Configuration Properties module - 1.2.5
- Secure Properties tool - 4.5
- Tracing Module - 1.0.0

* Page #6 [MuleSoft products, components, and tools used in this course]
- Maven-3.9.4
- Maven Resources plugin - 3.3.1

*  All references to the following must be replaced appropriately throughout the exercise guide
- replace "Studio 7.15.0" with "Studio 7.16.0"
- replace "Mule runtime 4.4.0 EE" with "Mule runtime 4.5.0 EE"

*  Replace all references to "<app.runtime.semver>" with "<app.runtime>" (because we no longer use Date-based syntax for Mule server version)

*  WT-2.4
  - Page: 101
    - The version of secure properties tool should use "4.5" in place of "4.4".  For example, the location of jar tool is at: https://docs.mulesoft.com/mule-runtime/4.5/_attachments/secure-properties-tool.jar
```