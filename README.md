# Microsoft Windows 10 (microsoft-windows-10)

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Collection of APIs and developer resources for building applications on the Windows 10 platform, including Universal Windows Platform (UWP), Win32, and Windows Runtime APIs for desktop, mobile, and IoT applications.

**APIs.json:** [https://developer.microsoft.com/en-us/windows/](https://developer.microsoft.com/en-us/windows/)

## Scope

- **Type:** Index

## Tags

- Desktop
- Operating System
- UWP
- Win32
- Windows

## Timestamps

- **Created:** 2024-01-01
- **Modified:** 2026-05-19

## APIs

### Windows Runtime (WinRT) API

Modern API surface for building Universal Windows Platform (UWP) applications that run across all Windows 10 device families. WinRT provides a type system, APIs, and runtime environment for building apps using C#, C++, Visual Basic, and JavaScript.

- **Human URL:** [https://learn.microsoft.com/en-us/windows/uwp/](https://learn.microsoft.com/en-us/windows/uwp/)
- **Base URL:** `https://api.windows.com`

#### Tags

- Universal Apps
- UWP
- Windows Runtime
- WinRT

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/uwp/api/)
- [Getting Started](https://learn.microsoft.com/en-us/windows/uwp/get-started/)
- [Samples](https://github.com/Microsoft/Windows-universal-samples)
- [Reference](https://learn.microsoft.com/en-us/uwp/api/)
- [S D Ks](https://developer.microsoft.com/en-us/windows/downloads/windows-10-sdk/)
- [OpenAPI](openapi/microsoft-windows-10-winrt-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-windows-10-winrt.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-windows-10-winrt.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Win32 API

Core Windows API for building traditional desktop applications using C and C++. Win32 provides direct access to system-level functionality including window management, graphics, networking, and hardware.

- **Human URL:** [https://learn.microsoft.com/en-us/windows/win32/](https://learn.microsoft.com/en-us/windows/win32/)
- **Base URL:** `https://api.windows.com`

#### Tags

- Desktop
- Native
- System Programming
- Win32

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/windows/win32/apiindex/windows-api-list)
- [Reference](https://learn.microsoft.com/en-us/windows/win32/api/)
- [Samples](https://github.com/microsoft/Windows-classic-samples)
- [Getting Started](https://learn.microsoft.com/en-us/windows/win32/desktop-programming)
- [OpenAPI](openapi/microsoft-windows-10-win32-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-windows-10-win32.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-windows-10-win32.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Windows Notifications API

API for sending and managing toast notifications, tile notifications, and badge updates in Windows 10 applications. Supports adaptive and interactive notifications with custom layouts, actions, and scheduling.

- **Human URL:** [https://learn.microsoft.com/en-us/windows/uwp/design/shell/tiles-and-notifications/](https://learn.microsoft.com/en-us/windows/uwp/design/shell/tiles-and-notifications/)
- **Base URL:** `https://api.windows.com`

#### Tags

- Notifications
- Tiles
- Toast
- User Interface

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/windows/uwp/design/shell/tiles-and-notifications/adaptive-interactive-toasts)
- [Samples](https://github.com/WindowsNotifications/quickstart-sending-local-toast-win10)
- [Reference](https://learn.microsoft.com/en-us/uwp/api/windows.ui.notifications)
- [OpenAPI](openapi/microsoft-windows-10-notifications-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-windows-10-notifications.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-windows-10-notifications.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Windows ML API

API for integrating trained machine learning models into Windows applications using the ONNX format. Windows ML evaluates models locally on the device using hardware acceleration with DirectX 12.

- **Human URL:** [https://learn.microsoft.com/en-us/windows/ai/windows-ml/](https://learn.microsoft.com/en-us/windows/ai/windows-ml/)
- **Base URL:** `https://api.windows.com`

#### Tags

- Artificial Intelligence
- Inference
- Machine Learning
- ONNX

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/windows/ai/windows-ml/api-reference)
- [Tutorials](https://learn.microsoft.com/en-us/windows/ai/windows-ml/tutorials)
- [Samples](https://github.com/Microsoft/Windows-Machine-Learning)
- [Getting Started](https://learn.microsoft.com/en-us/windows/ai/windows-ml/get-started)
- [OpenAPI](openapi/microsoft-windows-10-ml-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-windows-10-ml.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-windows-10-ml.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Windows Storage API

API for file system access, storage management, and data operations in Windows applications. Provides classes for reading, writing, and managing files and folders with appropriate access permissions.

- **Human URL:** [https://learn.microsoft.com/en-us/windows/uwp/files/](https://learn.microsoft.com/en-us/windows/uwp/files/)
- **Base URL:** `https://api.windows.com`

#### Tags

- Data Management
- File System
- Files
- Storage

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/uwp/api/windows.storage)
- [Best  Practices](https://learn.microsoft.com/en-us/windows/uwp/files/best-practices-for-writing-to-files)
- [Getting Started](https://learn.microsoft.com/en-us/windows/uwp/files/)
- [OpenAPI](openapi/microsoft-windows-10-storage-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-windows-10-storage.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-windows-10-storage.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Windows Cortana API

API for integrating voice commands and Cortana digital assistant capabilities into Windows applications. Enables voice-activated interactions and custom voice command definitions.

- **Human URL:** [https://learn.microsoft.com/en-us/cortana/](https://learn.microsoft.com/en-us/cortana/)
- **Base URL:** `https://api.windows.com`

#### Tags

- Cortana
- Digital Assistant
- Voice
- Voice Commands

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/cortana/voice-commands/vcd)
- [Guidelines](https://learn.microsoft.com/en-us/cortana/voice-commands/voicecommand-design-guidelines)
- [OpenAPI](openapi/microsoft-windows-10-cortana-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-windows-10-cortana.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-windows-10-cortana.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Windows Ink API

API for pen and stylus input in Windows applications, providing inking surfaces, stroke recognition, and handwriting analysis. Supports pressure sensitivity, tilt, and barrel button interactions.

- **Human URL:** [https://learn.microsoft.com/en-us/windows/uwp/design/input/pen-and-stylus-interactions](https://learn.microsoft.com/en-us/windows/uwp/design/input/pen-and-stylus-interactions)
- **Base URL:** `https://api.windows.com`

#### Tags

- Ink
- Input
- Pen
- Stylus

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/uwp/api/windows.ui.input.inking)
- [Samples](https://github.com/Microsoft/Windows-universal-samples/tree/master/Samples/SimpleInk)
- [Getting Started](https://learn.microsoft.com/en-us/windows/uwp/design/input/pen-and-stylus-interactions)
- [OpenAPI](openapi/microsoft-windows-10-ink-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-windows-10-ink.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-windows-10-ink.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Windows Composition API

The Windows.UI.Composition API provides access to the visual layer between the XAML framework and the DirectX graphics layer. It enables high-performance, retained-mode graphics, effects, and animations as the foundation for UI across Windows devices.

- **Human URL:** [https://learn.microsoft.com/en-us/windows/uwp/composition/visual-layer](https://learn.microsoft.com/en-us/windows/uwp/composition/visual-layer)
- **Base URL:** `https://api.windows.com`

#### Tags

- Animations
- Composition
- Graphics
- Visual Layer

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/windows/uwp/composition/visual-layer)
- [Reference](https://learn.microsoft.com/en-us/uwp/api/windows.ui.composition)
- [Samples](https://github.com/microsoft/Windows.UI.Composition-Win32-Samples)
- [Getting Started](https://learn.microsoft.com/en-us/windows/uwp/composition/using-the-visual-layer-with-xaml)
- [OpenAPI](openapi/microsoft-windows-10-composition-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-windows-10-composition.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-windows-10-composition.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### DirectX Graphics API

Low-level graphics API for building high-performance 2D and 3D rendering in Windows applications. Includes Direct3D for 3D graphics, Direct2D for 2D graphics, and DirectWrite for text rendering.

- **Human URL:** [https://learn.microsoft.com/en-us/windows/win32/directx](https://learn.microsoft.com/en-us/windows/win32/directx)
- **Base URL:** `https://api.windows.com`

#### Tags

- DirectX
- Gaming
- Graphics
- Rendering

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/windows/win32/directx)
- [Getting Started](https://learn.microsoft.com/en-us/windows/win32/getting-started-with-directx-graphics)
- [Samples](https://github.com/microsoft/DirectX-Graphics-Samples)
- [Reference](https://microsoft.github.io/DirectX-Specs/)
- [OpenAPI](openapi/microsoft-windows-10-directx-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-windows-10-directx.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-windows-10-directx.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Windows Media Capture API

API for capturing photos, audio, and video from camera and microphone devices in Windows applications. Provides classes for previewing, recording, and processing media streams with configurable encoding settings.

- **Human URL:** [https://learn.microsoft.com/en-us/windows/apps/develop/audio-video-camera](https://learn.microsoft.com/en-us/windows/apps/develop/audio-video-camera)
- **Base URL:** `https://api.windows.com`

#### Tags

- Audio
- Camera
- Media
- Video Capture

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/windows/apps/develop/audio-video-camera)
- [Reference](https://learn.microsoft.com/en-us/uwp/api/windows.media.capture)
- [Getting Started](https://learn.microsoft.com/en-us/windows/win32/medfound/audio-video-capture-in-media-foundation)
- [OpenAPI](openapi/microsoft-windows-10-media-capture-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-windows-10-media-capture.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-windows-10-media-capture.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Windows Networking API

API for network communication in Windows applications, providing support for sockets, WebSockets, HTTP clients, and background transfers. Enables TCP/UDP communication and real-time data streaming.

- **Human URL:** [https://learn.microsoft.com/en-us/windows/uwp/networking/](https://learn.microsoft.com/en-us/windows/uwp/networking/)
- **Base URL:** `https://api.windows.com`

#### Tags

- HTTP
- Networking
- Sockets
- WebSockets

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/windows/uwp/networking/which-networking-technology)
- [Reference](https://learn.microsoft.com/en-us/uwp/api/windows.networking.sockets)
- [Samples](https://learn.microsoft.com/en-us/samples/microsoft/windows-universal-samples/websocket/)
- [OpenAPI](openapi/microsoft-windows-10-networking-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-windows-10-networking.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-windows-10-networking.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Windows Bluetooth API

API for Bluetooth communication in Windows applications, supporting Bluetooth Classic (RFCOMM) and Bluetooth Low Energy (GATT) protocols for connecting to and exchanging data with Bluetooth devices.

- **Human URL:** [https://learn.microsoft.com/en-us/windows/uwp/devices-sensors/bluetooth](https://learn.microsoft.com/en-us/windows/uwp/devices-sensors/bluetooth)
- **Base URL:** `https://api.windows.com`

#### Tags

- Bluetooth
- Devices
- IoT
- Wireless

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/windows/uwp/devices-sensors/bluetooth-dev-faq)
- [Reference](https://learn.microsoft.com/en-us/windows/win32/api/_bluetooth/)
- [Getting Started](https://learn.microsoft.com/en-us/windows/win32/bluetooth/bluetooth-programming-with-windows-sockets)
- [OpenAPI](openapi/microsoft-windows-10-bluetooth-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-windows-10-bluetooth.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-windows-10-bluetooth.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Windows Geolocation API

API for obtaining geographic location data in Windows applications. Provides access to latitude, longitude, altitude, heading, and speed from GNSS, Wi-Fi, cellular networks, and IP address sources.

- **Human URL:** [https://learn.microsoft.com/en-us/windows/uwp/maps-and-location/](https://learn.microsoft.com/en-us/windows/uwp/maps-and-location/)
- **Base URL:** `https://api.windows.com`

#### Tags

- Geolocation
- GPS
- Location
- Maps

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/uwp/api/windows.devices.geolocation)
- [Reference](https://learn.microsoft.com/en-us/windows/win32/locationapi/windows-location-api-portal)
- [Samples](https://learn.microsoft.com/en-us/samples/microsoft/windows-universal-samples/geolocation/)
- [OpenAPI](openapi/microsoft-windows-10-geolocation-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-windows-10-geolocation.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-windows-10-geolocation.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Windows Sensors API

API for accessing device sensor data including accelerometer, gyroscope, compass, light sensor, and proximity sensor. Provides a unified interface for reading sensor values and responding to sensor events.

- **Human URL:** [https://learn.microsoft.com/en-us/windows/win32/sensorsapi/introduction-to-the-sensor-and-location-platform-in-windows](https://learn.microsoft.com/en-us/windows/win32/sensorsapi/introduction-to-the-sensor-and-location-platform-in-windows)
- **Base URL:** `https://api.windows.com`

#### Tags

- Devices
- Hardware
- IoT
- Sensors

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/windows/win32/sensorsapi/introduction-to-the-sensor-and-location-platform-in-windows)
- [Reference](https://learn.microsoft.com/en-us/uwp/api/windows.devices.sensors)
- [OpenAPI](openapi/microsoft-windows-10-sensors-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-windows-10-sensors.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-windows-10-sensors.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Windows Hello Authentication API

Biometric and PIN-based authentication API that replaces passwords with strong two-factor authentication. Supports facial recognition, fingerprint scanning, and PIN-based user verification for secure sign-in.

- **Human URL:** [https://learn.microsoft.com/en-us/windows/apps/develop/security/windows-hello](https://learn.microsoft.com/en-us/windows/apps/develop/security/windows-hello)
- **Base URL:** `https://api.windows.com`

#### Tags

- Authentication
- Biometrics
- Identity
- Security

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/windows/apps/develop/security/windows-hello)
- [Getting Started](https://learn.microsoft.com/en-us/windows/apps/develop/security/windows-hello-auth-service)
- [Reference](https://learn.microsoft.com/en-us/windows/security/identity-protection/hello-for-business/webauthn-apis)
- [OpenAPI](openapi/microsoft-windows-10-hello-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-windows-10-hello.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-windows-10-hello.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### WinUI API

Modern native UI framework for building Windows desktop applications with the Fluent Design System. WinUI provides XAML-based controls, high-performance rendering, and supports both C# and C++ development.

- **Human URL:** [https://learn.microsoft.com/en-us/windows/apps/winui/winui2/](https://learn.microsoft.com/en-us/windows/apps/winui/winui2/)
- **Base URL:** `https://api.windows.com`

#### Tags

- Controls
- Fluent Design
- User Interface
- XAML

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/windows/apps/winui/winui2/)
- [Reference](https://learn.microsoft.com/en-us/windows/winui/api/microsoft.ui.xaml.controls)
- [Getting Started](https://learn.microsoft.com/en-us/windows/apps/winui/winui2/getting-started)
- [Samples](https://github.com/microsoft/microsoft-ui-xaml)
- [OpenAPI](openapi/microsoft-windows-10-winui-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-windows-10-winui.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-windows-10-winui.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Windows Background Tasks API

API for running code in the background when an application is suspended or not running. Supports time-triggered, system-triggered, and maintenance-triggered background tasks for continuous processing.

- **Human URL:** [https://learn.microsoft.com/en-us/windows/apps/windows-app-sdk/applifecycle/background-tasks](https://learn.microsoft.com/en-us/windows/apps/windows-app-sdk/applifecycle/background-tasks)
- **Base URL:** `https://api.windows.com`

#### Tags

- App Lifecycle
- Background Tasks
- Scheduling

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/windows/apps/windows-app-sdk/applifecycle/background-tasks)
- [Samples](https://learn.microsoft.com/en-us/samples/microsoft/windows-universal-samples/backgroundtask/)
- [OpenAPI](openapi/microsoft-windows-10-background-tasks-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/microsoft-windows-10-background-tasks.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/microsoft-windows-10-background-tasks.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Portal](https://developer.microsoft.com/en-us/windows/)
- [Documentation](https://learn.microsoft.com/en-us/windows/apps/)
- [Getting Started](https://learn.microsoft.com/en-us/windows/apps/get-started/)
- [Authentication](https://learn.microsoft.com/en-us/windows/apps/develop/security/windows-hello)
- [Blog](https://blogs.windows.com/windowsdeveloper/)
- [Status Page](https://status.cloud.microsoft/)
- [Support](https://developer.microsoft.com/en-us/windows/support)
- [Terms of Service](https://www.microsoft.com/en-us/legal/terms-of-use)
- [Privacy Policy](https://www.microsoft.com/en-us/privacy/privacystatement)
- [GitHub Organization](https://github.com/microsoft)
- [Community](https://developer.microsoft.com/en-us/windows/community/)
- [Website](https://www.microsoft.com)
- [Login](https://login.microsoftonline.com/)
- [Sign Up](https://developer.microsoft.com/en-us/)
- [S D Ks](https://developer.microsoft.com/en-us/windows/downloads/windows-10-sdk/)
- [Changelog](https://learn.microsoft.com/en-us/windows/apps/whats-new/whats-new-for-developers)
- [Reference](https://learn.microsoft.com/en-us/windows/apps/api-reference/)
- [JSON-LD](json-ld/microsoft-windows-10-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/microsoft-windows-10-notification-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/microsoft-windows-10-storage-item-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/microsoft-windows-10-geolocation-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/microsoft-windows-10-sensor-reading-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/microsoft-windows-10-ml-model-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/microsoft-windows-10-bluetooth-device-schema.json) — [JSON Schema](https://json-schema.org/specification)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
