# Hi, I'm Chit 👋

Product-minded problem solver interested in turning ambiguous technical challenges and overlooked product opportunities into practical, validated improvements.

🎓 **MSc MIS & Digital Innovation**

My hands-on work has mainly involved **systems integration, interoperability, open-source investigation, and product-focused technical problem solving**. I'm currently exploring **AI implementation and agent workflows**, particularly how they can be integrated into real products and working processes.

## Featured Open-Source Contribution

### 🎮 VoidLink — Real physical rumble for GameSir G8+ MFi on iOS

I contributed the **first publicly merged implementation enabling real physical dual-motor rumble for the GameSir G8+ MFi in iOS game streaming**.

The controller worked normally for input, but the standard iOS GameController/Core Haptics path did not drive its physical motors. I investigated the hardware behaviour, identified its wired ExternalAccessory interface, experimentally validated independent left/right motor control, and implemented a device-specific rumble backend for VoidLink.

- **Problem** → input worked, physical rumble did not
- **Investigation** → identified and validated the wired ExternalAccessory control path
- **Implementation** → added independent dual-motor control with queueing, lifecycle handling, and graceful fallback
- **Validation** → tested across firmware versions and sustained real-game Sunshine streaming
- **Outcome** → **reviewed and merged upstream in [PR #214](https://github.com/The-Fried-Fish/VoidLink-previously-moonlight-zwm/pull/214)**

[View the merged upstream PR](https://github.com/The-Fried-Fish/VoidLink-previously-moonlight-zwm/pull/214) · [Explore the upstream VoidLink repository](https://github.com/The-Fried-Fish/VoidLink-previously-moonlight-zwm)

## Open Source & Community

I like contributing back to open-source tools I actually use. I pay attention not only to what breaks, but also to what could work better — spotting friction, interaction gaps, and product opportunities, then turning those observations into reproducible reports, concrete suggestions, experiments, and, when possible, upstream solutions.

### OpenLess — [Issue #934](https://github.com/Open-Less/openless/issues/934)

Authored and scoped a reproducible long-session macOS recording-cue failure with environment details, source-level tracing, and acceptance criteria. Maintainers subsequently isolated degraded WebKit AudioContext behaviour and developed regression coverage.

### EasyDict — [Issue #77](https://github.com/tisfeng/Easydict/issues/77)

Contributed cross-version reproduction evidence for a DeepL Traditional Chinese regression across multiple translation modes. The maintainer traced it to conversion logic lost during an API refactor and marked it for a release fix.

### OpenCode — [Issue #9790](https://github.com/anomalyco/opencode/issues/9790)

Contributed root-cause diagnosis to a Windows terminal interaction issue affecting multiple users, identifying an external Cherry Studio selection-helper interaction that was injecting unintended `Ctrl+C` input and sharing a practical mitigation.

## Current Focus

**AI implementation & agent workflows** · **Product problem solving** · **Technical integration & interoperability**

## Connect

[Portfolio](https://ab76.md/) · [LinkedIn](https://www.linkedin.com/in/chrischitheing/) · [Email](mailto:chithei.ng@outlook.com)
