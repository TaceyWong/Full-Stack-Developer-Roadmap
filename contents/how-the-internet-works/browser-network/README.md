*From: https://hpbn.co/ *


# High Performance Browser Networking | 高性能浏览器网络


Performance is a feature. This book provides a hands-on overview of what every web developer needs to know about the various types of networks (WiFi, 3G/4G), transport protocols (UDP, TCP, and TLS), application protocols (HTTP/1.1, HTTP/2), and APIs available in the browser (XHR, WebSocket, WebRTC, and more) to deliver the best—fast, reliable, and resilient—user experience.

>> This book is required reading for anyone who cares about web performance; it's already established as the go-to reference on the topic. —Mark Nottingham (IETF HTTPBis Chair)




## Table of Contents

### Networking 101 | 网络初步

1. #### [Primer on Latency and Bandwidth](https://hpbn.co/primer-on-latency-and-bandwidth/)

   - ##### [Speed Is a Feature](https://hpbn.co/primer-on-latency-and-bandwidth/#speed-is-a-feature)

   - ##### [The Many Components of Latency](https://hpbn.co/primer-on-latency-and-bandwidth/#the-many-components-of-latency)

   - ##### [Speed of Light and Propagation Latency](https://hpbn.co/primer-on-latency-and-bandwidth/#speed-of-light-and-propagation-latency)

   - ##### [Last-Mile Latency](https://hpbn.co/primer-on-latency-and-bandwidth/#last-mile-latency)

   - ##### [Bandwidth in Core Networks](https://hpbn.co/primer-on-latency-and-bandwidth/#bandwidth-in-core-networks)

   - ##### [Bandwidth at the Network Edge](https://hpbn.co/primer-on-latency-and-bandwidth/#bandwidth-at-the-network-edge)

   - ##### [Delivering Higher Bandwidth and Lower Latencies](https://hpbn.co/primer-on-latency-and-bandwidth/#delivering-higher-bandwidth-and-lower-latencies)

2. #### [Building Blocks of TCP](https://hpbn.co/building-blocks-of-tcp/)

   - ##### [Three-Way Handshake](https://hpbn.co/building-blocks-of-tcp/#three-way-handshake)

   - \-

     ##### [Congestion Avoidance and Control](https://hpbn.co/building-blocks-of-tcp/#congestion-avoidance-and-control)

     - ###### [Flow Control](https://hpbn.co/building-blocks-of-tcp/#flow-control)

     - ###### [Slow-Start](https://hpbn.co/building-blocks-of-tcp/#slow-start)

     - ###### [Congestion Avoidance](https://hpbn.co/building-blocks-of-tcp/#congestion-avoidance)

   - ##### [Bandwidth-Delay Product](https://hpbn.co/building-blocks-of-tcp/#bandwidth-delay-product)

   - ##### [Head-of-Line Blocking](https://hpbn.co/building-blocks-of-tcp/#head-of-line-blocking)

   - \-

     ##### [Optimizing for TCP](https://hpbn.co/building-blocks-of-tcp/#optimizing-for-tcp)

     - ###### [Tuning Server Configuration](https://hpbn.co/building-blocks-of-tcp/#tuning-server-configuration)

     - ###### [Tuning Application Behavior](https://hpbn.co/building-blocks-of-tcp/#tuning-application-behavior)

     - ###### [Performance Checklist](https://hpbn.co/building-blocks-of-tcp/#performance-checklist)

3. #### [Building Blocks of UDP](https://hpbn.co/building-blocks-of-udp/)

   - ##### [Null Protocol Services](https://hpbn.co/building-blocks-of-udp/#null-protocol-services)

   - \-

     ##### [UDP and Network Address Translators](https://hpbn.co/building-blocks-of-udp/#udp-and-network-address-translators)

     - ###### [Connection-State Timeouts](https://hpbn.co/building-blocks-of-udp/#connection-state-timeouts)

     - ###### [NAT Traversal](https://hpbn.co/building-blocks-of-udp/#nat-traversal)

     - ###### [STUN, TURN, and ICE](https://hpbn.co/building-blocks-of-udp/#stun-turn-and-ice)

   - ##### [Optimizing for UDP](https://hpbn.co/building-blocks-of-udp/#optimizing-for-udp)

4. #### [Transport Layer Security (TLS)](https://hpbn.co/transport-layer-security-tls/)

   - ##### [Encryption, Authentication, and Integrity](https://hpbn.co/transport-layer-security-tls/#encryption-authentication-and-integrity)

   - ##### [HTTPS Everywhere](https://hpbn.co/transport-layer-security-tls/#https-everywhere)

   - \-

     ##### [TLS Handshake](https://hpbn.co/transport-layer-security-tls/#tls-handshake)

     - ###### [RSA, Diffie-Hellman and Forward Secrecy](https://hpbn.co/transport-layer-security-tls/#rsa-diffie-hellman-and-forward-secrecy)

     - ###### [Application Layer Protocol Negotiation (ALPN)](https://hpbn.co/transport-layer-security-tls/#application-layer-protocol-negotiation-alpn)

     - ###### [Server Name Indication (SNI)](https://hpbn.co/transport-layer-security-tls/#server-name-indication-sni)

   - \-

     ##### [TLS Session Resumption](https://hpbn.co/transport-layer-security-tls/#tls-session-resumption)

     - ###### [Session Identifiers](https://hpbn.co/transport-layer-security-tls/#session-identifiers)

     - ###### [Session Tickets](https://hpbn.co/transport-layer-security-tls/#session-tickets)

   - ##### [Chain of Trust and Certificate Authorities](https://hpbn.co/transport-layer-security-tls/#chain-of-trust-and-certificate-authorities)

   - \-

     ##### [Certificate Revocation](https://hpbn.co/transport-layer-security-tls/#certificate-revocation)

     - ###### [Certificate Revocation List (CRL)](https://hpbn.co/transport-layer-security-tls/#certificate-revocation-list-crl)

     - ###### [Online Certificate Status Protocol (OCSP)](https://hpbn.co/transport-layer-security-tls/#online-certificate-status-protocol-ocsp)

     - ###### [OCSP Stapling](https://hpbn.co/transport-layer-security-tls/#ocsp-stapling)

   - ##### [TLS Record Protocol](https://hpbn.co/transport-layer-security-tls/#tls-record-protocol)

   - \-

     ##### [Optimizing for TLS](https://hpbn.co/transport-layer-security-tls/#optimizing-for-tls)

     - ###### [Reduce Computational Costs](https://hpbn.co/transport-layer-security-tls/#reduce-computational-costs)

     - ###### [Enable 1-RTT TLS Handshakes](https://hpbn.co/transport-layer-security-tls/#enable-1-rtt-tls-handshakes)

     - ###### [Optimize Connection Reuse](https://hpbn.co/transport-layer-security-tls/#optimize-connection-reuse)

     - ###### [Leverage Early Termination](https://hpbn.co/transport-layer-security-tls/#leverage-early-termination)

     - ###### [Configure Session Caching and Stateless Resumption](https://hpbn.co/transport-layer-security-tls/#configure-session-caching-and-stateless-resumption)

     - ###### [Enable TLS False Start](https://hpbn.co/transport-layer-security-tls/#enable-tls-false-start)

     - ###### [Optimize TLS Record Size](https://hpbn.co/transport-layer-security-tls/#optimize-tls-record-size)

     - ###### [Optimize the Certificate Chain](https://hpbn.co/transport-layer-security-tls/#optimize-the-certificate-chain)

     - ###### [Configure OCSP Stapling](https://hpbn.co/transport-layer-security-tls/#configure-ocsp-stapling)

     - ###### [Enable HTTP Strict Transport Security (HSTS)](https://hpbn.co/transport-layer-security-tls/#enable-http-strict-transport-security-hsts)

     - ###### [Enable HTTP Public Key Pinning (HPKP)](https://hpbn.co/transport-layer-security-tls/#enable-http-public-key-pinning-hpkp)

     - ###### [Update Site Content to HTTPS](https://hpbn.co/transport-layer-security-tls/#update-site-content-to-https)

     - ###### [Performance Checklist](https://hpbn.co/transport-layer-security-tls/#performance-checklist)

   - ##### [Testing and Verification](https://hpbn.co/transport-layer-security-tls/#testing-and-verification)

### Performance of Wireless Networks

1. #### [Introduction to Wireless Networks](https://hpbn.co/introduction-to-wireless-networks/)

   - ##### [Ubiquitous Connectivity](https://hpbn.co/introduction-to-wireless-networks/#ubiquitous-connectivity)

   - ##### [Types of Wireless Networks](https://hpbn.co/introduction-to-wireless-networks/#types-of-wireless-networks)

   - \-

     ##### [Performance Fundamentals of Wireless Networks](https://hpbn.co/introduction-to-wireless-networks/#performance-fundamentals-of-wireless-networks)

     - ###### [Bandwidth](https://hpbn.co/introduction-to-wireless-networks/#bandwidth)

     - ###### [Signal Power](https://hpbn.co/introduction-to-wireless-networks/#signal-power)

     - ###### [Modulation](https://hpbn.co/introduction-to-wireless-networks/#modulation)

   - ##### [Measuring Real-World Wireless Performance](https://hpbn.co/introduction-to-wireless-networks/#measuring-real-world-wireless-performance)

2. #### [WiFi](https://hpbn.co/wifi/)

   - ##### [From Ethernet to a Wireless LAN](https://hpbn.co/wifi/#from-ethernet-to-a-wireless-lan)

   - ##### [WiFi Standards and Features](https://hpbn.co/wifi/#wifi-standards-and-features)

   - \-

     ##### [Measuring and Optimizing WiFi Performance](https://hpbn.co/wifi/#measuring-and-optimizing-wifi-performance)

     - ###### [Packet Loss in WiFi Networks](https://hpbn.co/wifi/#packet-loss-in-wifi-networks)

   - \-

     ##### [Optimizing for WiFi Networks](https://hpbn.co/wifi/#optimizing-for-wifi-networks)

     - ###### [Leverage Unmetered Bandwidth](https://hpbn.co/wifi/#leverage-unmetered-bandwidth)

     - ###### [Adapt to Variable Bandwidth](https://hpbn.co/wifi/#adapt-to-variable-bandwidth)

     - ###### [Adapt to Variable Latency](https://hpbn.co/wifi/#adapt-to-variable-latency)

3. #### [Mobile Networks](https://hpbn.co/mobile-networks/)

   - \-

     ##### [Brief History of the G’s](https://hpbn.co/mobile-networks/#brief-history-of-the-gs)

     - ###### [First Data Services with 2G](https://hpbn.co/mobile-networks/#first-data-services-with-2g)

     - ###### [3GPP and 3GPP2 Partnerships](https://hpbn.co/mobile-networks/#3gpp-and-3gpp2-partnerships)

     - ###### [Evolution of 3G Technologies](https://hpbn.co/mobile-networks/#evolution-of-3g-technologies)

     - ###### [IMT-Advanced 4G Requirements](https://hpbn.co/mobile-networks/#imt-advanced-4g-requirements)

     - ###### [Long Term Evolution (LTE)](https://hpbn.co/mobile-networks/#long-term-evolution-lte)

     - ###### [HSPA+ is Leading Worldwide 4G Adoption](https://hpbn.co/mobile-networks/#hspa-is-leading-worldwide-4g-adoption)

     - ###### [Building for the Multigeneration Future](https://hpbn.co/mobile-networks/#building-for-the-multigeneration-future)

   - \-

     ##### [Device Features and Capabilities](https://hpbn.co/mobile-networks/#device-features-and-capabilities)

     - ###### [User Equipment Category](https://hpbn.co/mobile-networks/#user-equipment-category)

   - \-

     ##### [Radio Resource Controller (RRC)](https://hpbn.co/mobile-networks/#radio-resource-controller-rrc)

     - ###### [3G, 4G, and WiFi Power Requirements](https://hpbn.co/mobile-networks/#3g-4g-and-wifi-power-requirements)

     - ###### [LTE RRC State Machine](https://hpbn.co/mobile-networks/#lte-rrc-state-machine)

     - ###### [HSPA and HSPA+ (UMTS) RRC State Machine](https://hpbn.co/mobile-networks/#hspa-and-hspa-umts-rrc-state-machine)

     - ###### [EV-DO (CDMA) RRC State Machine](https://hpbn.co/mobile-networks/#ev-do-cdma-rrc-state-machine)

     - ###### [Inefficiency of Periodic Transfers](https://hpbn.co/mobile-networks/#inefficiency-of-periodic-transfers)

   - \-

     ##### [End-to-End Carrier Architecture](https://hpbn.co/mobile-networks/#end-to-end-carrier-architecture)

     - ###### [Radio Access Network (RAN)](https://hpbn.co/mobile-networks/#radio-access-network-ran)

     - ###### [Core Network (CN)](https://hpbn.co/mobile-networks/#core-network-cn)

     - ###### [Backhaul Capacity and Latency](https://hpbn.co/mobile-networks/#backhaul-capacity-and-latency)

   - \-

     ##### [Packet Flow in a Mobile Network](https://hpbn.co/mobile-networks/#packet-flow-in-a-mobile-network)

     - ###### [Initiating a Request](https://hpbn.co/mobile-networks/#initiating-a-request)

     - ###### [Inbound Data Flow](https://hpbn.co/mobile-networks/#inbound-data-flow)

   - ##### [Heterogeneous Networks (HetNets)](https://hpbn.co/mobile-networks/#heterogeneous-networks-hetnets)

   - ##### [Real-World 3G, 4G, and WiFi Performance](https://hpbn.co/mobile-networks/#real-world-3g-4g-and-wifi-performance)

4. #### [Optimizing for Mobile Networks](https://hpbn.co/optimizing-for-mobile-networks/)

   - ##### [Preserve Battery Power](https://hpbn.co/optimizing-for-mobile-networks/#preserve-battery-power)

   - \-

     ##### [Eliminate Periodic and Inefficient Data Transfers](https://hpbn.co/optimizing-for-mobile-networks/#eliminate-periodic-and-inefficient-data-transfers)

     - ###### [Eliminate Unnecessary Application Keepalives](https://hpbn.co/optimizing-for-mobile-networks/#eliminate-unnecessary-application-keepalives)

   - \-

     ##### [Anticipate Network Latency Overhead](https://hpbn.co/optimizing-for-mobile-networks/#anticipate-network-latency-overhead)

     - ###### [Account for RRC State Transitions](https://hpbn.co/optimizing-for-mobile-networks/#account-for-rrc-state-transitions)

     - ###### [Decouple User Interactions from Network Communication](https://hpbn.co/optimizing-for-mobile-networks/#decouple-user-interactions-from-network-communication)

   - ##### [Design for Variable Network Interface Availability](https://hpbn.co/optimizing-for-mobile-networks/#design-for-variable-network-interface-availability)

   - ##### [Burst Your Data and Return to Idle](https://hpbn.co/optimizing-for-mobile-networks/#burst-your-data-and-return-to-idle)

   - ##### [Offload to WiFi Networks](https://hpbn.co/optimizing-for-mobile-networks/#offload-to-wifi-networks)

   - ##### [Apply Protocol and Application Best Practices](https://hpbn.co/optimizing-for-mobile-networks/#apply-protocol-and-application-best-practices)

### HTTP

1. #### [Brief History of HTTP](https://hpbn.co/brief-history-of-http/)

   - ##### [HTTP 0.9: The One-Line Protocol](https://hpbn.co/brief-history-of-http/#http-09-the-one-line-protocol)

   - ##### [HTTP/1.0: Rapid Growth and Informational RFC](https://hpbn.co/brief-history-of-http/#http10-rapid-growth-and-informational-rfc)

   - ##### [HTTP/1.1: Internet Standard](https://hpbn.co/brief-history-of-http/#http11-internet-standard)

   - ##### [HTTP/2: Improving Transport Performance](https://hpbn.co/brief-history-of-http/#http2-improving-transport-performance)

2. #### [Primer on Web Performance](https://hpbn.co/primer-on-web-performance/)

   - ##### [Hypertext, Web Pages, and Web Applications](https://hpbn.co/primer-on-web-performance/#hypertext-web-pages-and-web-applications)

   - \-

     ##### [Anatomy of a Modern Web Application](https://hpbn.co/primer-on-web-performance/#anatomy-of-a-modern-web-application)

     - ###### [Speed, Performance, and Human Perception](https://hpbn.co/primer-on-web-performance/#speed-performance-and-human-perception)

     - ###### [Analyzing the Resource Waterfall](https://hpbn.co/primer-on-web-performance/#analyzing-the-resource-waterfall)

   - \-

     ##### [Performance Pillars: Computing, Rendering, Networking](https://hpbn.co/primer-on-web-performance/#performance-pillars-computing-rendering-networking)

     - ###### [More Bandwidth Doesn’t Matter (Much)](https://hpbn.co/primer-on-web-performance/#more-bandwidth-doesnt-matter-much)

     - ###### [Latency as a Performance Bottleneck](https://hpbn.co/primer-on-web-performance/#latency-as-a-performance-bottleneck)

   - ##### [Synthetic and Real-User Performance Measurement](https://hpbn.co/primer-on-web-performance/#synthetic-and-real-user-performance-measurement)

   - ##### [Browser Optimization](https://hpbn.co/primer-on-web-performance/#browser-optimization)

3. #### [HTTP/1.X](https://hpbn.co/http1x/)

   - ##### [Benefits of Keepalive Connections](https://hpbn.co/http1x/#benefits-of-keepalive-connections)

   - ##### [HTTP Pipelining](https://hpbn.co/http1x/#http-pipelining)

   - ##### [Using Multiple TCP Connections](https://hpbn.co/http1x/#using-multiple-tcp-connections)

   - ##### [Domain Sharding](https://hpbn.co/http1x/#domain-sharding)

   - ##### [Measuring and Controlling Protocol Overhead](https://hpbn.co/http1x/#measuring-and-controlling-protocol-overhead)

   - ##### [Concatenation and Spriting](https://hpbn.co/http1x/#concatenation-and-spriting)

   - ##### [Resource Inlining](https://hpbn.co/http1x/#resource-inlining)

4. #### [HTTP/2](https://hpbn.co/http2/)

   - ##### [Brief History of SPDY and HTTP/2](https://hpbn.co/http2/#brief-history-of-spdy-and-http2)

   - ##### [Design and Technical Goals](https://hpbn.co/http2/#design-and-technical-goals)

   - ##### [Binary Framing Layer](https://hpbn.co/http2/#binary-framing-layer)

   - ##### [Streams, Messages, and Frames](https://hpbn.co/http2/#streams-messages-and-frames)

   - ##### [Request and Response Multiplexing](https://hpbn.co/http2/#request-and-response-multiplexing)

   - ##### [Stream Prioritization](https://hpbn.co/http2/#stream-prioritization)

   - ##### [One Connection Per Origin](https://hpbn.co/http2/#one-connection-per-origin)

   - ##### [Flow Control](https://hpbn.co/http2/#flow-control)

   - ##### [Server Push](https://hpbn.co/http2/#server-push)

   - ##### [Header Compression](https://hpbn.co/http2/#header-compression)

   - ##### [Upgrading to HTTP/2](https://hpbn.co/http2/#upgrading-to-http2)

   - \-

     ##### [Brief Introduction to Binary Framing](https://hpbn.co/http2/#brief-introduction-to-binary-framing)

     - ###### [Initiating a New Stream](https://hpbn.co/http2/#initiating-a-new-stream)

     - ###### [Sending Application Data](https://hpbn.co/http2/#sending-application-data)

     - ###### [Analyzing HTTP/2 Frame Data Flow](https://hpbn.co/http2/#analyzing-http2-frame-data-flow)

5. #### [Optimizing Application Delivery](https://hpbn.co/optimizing-application-delivery/)

   - ##### [Optimizing Physical and Transport Layers](https://hpbn.co/optimizing-application-delivery/#optimizing-physical-and-transport-layers)

   - \-

     ##### [Evergreen Performance Best Practices](https://hpbn.co/optimizing-application-delivery/#evergreen-performance-best-practices)

     - ###### [Cache Resources on the Client](https://hpbn.co/optimizing-application-delivery/#cache-resources-on-the-client)

     - ###### [Compress Transferred Data](https://hpbn.co/optimizing-application-delivery/#compress-transferred-data)

     - ###### [Eliminate Unnecessary Request Bytes](https://hpbn.co/optimizing-application-delivery/#eliminate-unnecessary-request-bytes)

     - ###### [Parallelize Request and Response Processing](https://hpbn.co/optimizing-application-delivery/#parallelize-request-and-response-processing)

   - ##### [Optimizing for HTTP/1.x](https://hpbn.co/optimizing-application-delivery/#optimizing-for-http1x)

   - \-

     ##### [Optimizing for HTTP/2](https://hpbn.co/optimizing-application-delivery/#optimizing-for-http2)

     - ###### [Eliminate Domain Sharding](https://hpbn.co/optimizing-application-delivery/#eliminate-domain-sharding)

     - ###### [Minimize Concatenation and Image Spriting](https://hpbn.co/optimizing-application-delivery/#minimize-concatenation-and-image-spriting)

     - ###### [Eliminate Roundtrips with Server Push](https://hpbn.co/optimizing-application-delivery/#eliminate-roundtrips-with-server-push)

     - ###### [Test HTTP/2 Server Quality](https://hpbn.co/optimizing-application-delivery/#test-http2-server-quality)

### Browser APIs and Protocols

1. #### [Primer on Browser Networking](https://hpbn.co/primer-on-browser-networking/)

   - ##### [Connection Management and Optimization](https://hpbn.co/primer-on-browser-networking/#connection-management-and-optimization)

   - ##### [Network Security and Sandboxing](https://hpbn.co/primer-on-browser-networking/#network-security-and-sandboxing)

   - ##### [Resource and Client State Caching](https://hpbn.co/primer-on-browser-networking/#resource-and-client-state-caching)

   - ##### [Application APIs and Protocols](https://hpbn.co/primer-on-browser-networking/#application-apis-and-protocols)

2. #### [XMLHttpRequest](https://hpbn.co/xmlhttprequest/)

   - ##### [Brief History of XHR](https://hpbn.co/xmlhttprequest/#brief-history-of-xhr)

   - ##### [Cross-Origin Resource Sharing (CORS)](https://hpbn.co/xmlhttprequest/#cross-origin-resource-sharing-cors)

   - ##### [Downloading Data with XHR](https://hpbn.co/xmlhttprequest/#downloading-data-with-xhr)

   - ##### [Uploading Data with XHR](https://hpbn.co/xmlhttprequest/#uploading-data-with-xhr)

   - ##### [Monitoring Download and Upload Progress](https://hpbn.co/xmlhttprequest/#monitoring-download-and-upload-progress)

   - ##### [Streaming Data with XHR](https://hpbn.co/xmlhttprequest/#streaming-data-with-xhr)

   - \-

     ##### [Real-Time Notifications and Delivery](https://hpbn.co/xmlhttprequest/#real-time-notifications-and-delivery)

     - ###### [Polling with XHR](https://hpbn.co/xmlhttprequest/#polling-with-xhr)

     - ###### [Long-Polling with XHR](https://hpbn.co/xmlhttprequest/#long-polling-with-xhr)

   - ##### [XHR Use Cases and Performance](https://hpbn.co/xmlhttprequest/#xhr-use-cases-and-performance)

3. #### [Server-Sent Events (SSE)](https://hpbn.co/server-sent-events-sse/)

   - ##### [EventSource API](https://hpbn.co/server-sent-events-sse/#eventsource-api)

   - ##### [Event Stream Protocol](https://hpbn.co/server-sent-events-sse/#event-stream-protocol)

   - ##### [SSE Use Cases and Performance](https://hpbn.co/server-sent-events-sse/#sse-use-cases-and-performance)

4. #### [WebSocket](https://hpbn.co/websocket/)

   - \-

     ##### [WebSocket API](https://hpbn.co/websocket/#websocket-api)

     - ###### [WS and WSS URL Schemes](https://hpbn.co/websocket/#ws-and-wss-url-schemes)

     - ###### [Receiving Text and Binary Data](https://hpbn.co/websocket/#receiving-text-and-binary-data)

     - ###### [Sending Text and Binary Data](https://hpbn.co/websocket/#sending-text-and-binary-data)

     - ###### [Subprotocol Negotiation](https://hpbn.co/websocket/#subprotocol-negotiation)

   - \-

     ##### [WebSocket Protocol](https://hpbn.co/websocket/#websocket-protocol)

     - ###### [Binary Framing Layer](https://hpbn.co/websocket/#binary-framing-layer)

     - ###### [Protocol Extensions](https://hpbn.co/websocket/#protocol-extensions)

     - ###### [HTTP Upgrade Negotiation](https://hpbn.co/websocket/#http-upgrade-negotiation)

   - \-

     ##### [WebSocket Use Cases and Performance](https://hpbn.co/websocket/#websocket-use-cases-and-performance)

     - ###### [Request and Response Streaming](https://hpbn.co/websocket/#request-and-response-streaming)

     - ###### [Message Overhead](https://hpbn.co/websocket/#message-overhead)

     - ###### [Data Efficiency and Compression](https://hpbn.co/websocket/#data-efficiency-and-compression)

     - ###### [Custom Application Protocols](https://hpbn.co/websocket/#custom-application-protocols)

     - ###### [Deploying WebSocket Infrastructure](https://hpbn.co/websocket/#deploying-websocket-infrastructure)

   - ##### [Performance Checklist](https://hpbn.co/websocket/#performance-checklist)

5. #### [WebRTC](https://hpbn.co/webrtc/)

   - ##### [Standards and Development of WebRTC](https://hpbn.co/webrtc/#standards-and-development-of-webrtc)

   - \-

     ##### [Audio and Video Engines](https://hpbn.co/webrtc/#audio-and-video-engines)

     - ###### [Acquiring Audio and Video with getUserMedia](https://hpbn.co/webrtc/#acquiring-audio-and-video-with-getusermedia)

   - \-

     ##### [Real-Time Network Transports](https://hpbn.co/webrtc/#real-time-network-transports)

     - ###### [Brief Introduction to RTCPeerConnection API](https://hpbn.co/webrtc/#brief-introduction-to-rtcpeerconnection-api)

   - \-

     ##### [Establishing a Peer-to-Peer Connection](https://hpbn.co/webrtc/#establishing-a-peer-to-peer-connection)

     - ###### [Signaling and Session Negotiation](https://hpbn.co/webrtc/#signaling-and-session-negotiation)

     - ###### [Session Description Protocol (SDP)](https://hpbn.co/webrtc/#session-description-protocol-sdp)

     - ###### [Interactive Connectivity Establishment (ICE)](https://hpbn.co/webrtc/#interactive-connectivity-establishment-ice)

     - ###### [Incremental Provisioning (Trickle ICE)](https://hpbn.co/webrtc/#incremental-provisioning-trickle-ice)

     - ###### [Tracking ICE Gathering and Connectivity Status](https://hpbn.co/webrtc/#tracking-ice-gathering-and-connectivity-status)

     - ###### [Putting It All Together](https://hpbn.co/webrtc/#putting-it-all-together)

   - \-

     ##### [Delivering Media and Application Data](https://hpbn.co/webrtc/#delivering-media-and-application-data)

     - ###### [Secure Communication with DTLS](https://hpbn.co/webrtc/#secure-communication-with-dtls)

     - ###### [Delivering Media with SRTP and SRTCP](https://hpbn.co/webrtc/#delivering-media-with-srtp-and-srtcp)

     - ###### [Delivering application data with SCTP](https://hpbn.co/webrtc/#delivering-application-data-with-sctp)

   - \-

     ##### [DataChannel](https://hpbn.co/webrtc/#datachannel)

     - ###### [Setup and Negotiation](https://hpbn.co/webrtc/#setup-and-negotiation)

     - ###### [Configuring Message Order and Reliability](https://hpbn.co/webrtc/#configuring-message-order-and-reliability)

     - ###### [Partially Reliable Delivery and Message Size](https://hpbn.co/webrtc/#partially-reliable-delivery-and-message-size)

   - \-

     ##### [WebRTC Use Cases and Performance](https://hpbn.co/webrtc/#webrtc-use-cases-and-performance)

     - ###### [Audio, Video, and Data Streaming](https://hpbn.co/webrtc/#audio-video-and-data-streaming)

     - ###### [Multiparty Architectures](https://hpbn.co/webrtc/#multiparty-architectures)

     - ###### [Infrastructure and Capacity Planning](https://hpbn.co/webrtc/#infrastructure-and-capacity-planning)

     - ###### [Data Efficiency and Compression](https://hpbn.co/webrtc/#data-efficiency-and-compression)

   - ##### [Performance Checklist](https://hpbn.co/webrtc/#performance-checklist)

### [§](https://hpbn.co/#author)About the author

Ilya Grigorik is a web performance engineer at Google and co-chair of the W3C Web Performance Working Group. Follow him on [his blog](https://www.igvita.com/) and [Twitter](https://twitter.com/igrigorik) for the latest web performance news, tips, and talks.

