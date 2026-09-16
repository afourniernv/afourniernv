# Alex Fournier

AI Solution Architect at [NVIDIA](https://www.nvidia.com/) working across agent runtimes, observability, model routing, safety, evaluation, enterprise identity, and GPU-accelerated retrieval—primarily in Rust, Python, and TypeScript.

I contribute upstream to NVIDIA's agentic AI ecosystem and [Nous Research's Hermes Agent](https://github.com/NousResearch/hermes-agent). My focus is turning integrations into maintainable product paths: implementing the runtime boundary, testing it under real workloads, hardening failures and lifecycle behavior, and leaving behind documentation that other teams can use.

[LinkedIn](https://www.linkedin.com/in/alexander-fournier-aa8580139/) · [GitHub contributions](https://github.com/pulls?q=is%3Apr+author%3Aafourniernv+archived%3Afalse)

## Selected open-source work

### Hermes Agent and NeMo Relay

- Implemented and upstreamed Hermes Agent's core NeMo Relay integration, covering session and turn scopes, model and tool execution, streaming, delegated agents, opt-in observability, privacy boundaries, and shared metrics ([Hermes #67607](https://github.com/NousResearch/hermes-agent/pull/67607)).
- Hardened the integration after launch, including Anthropic callback handling ([Hermes #73120](https://github.com/NousResearch/hermes-agent/pull/73120)) and provider-error and scope cleanup ([Hermes #73493](https://github.com/NousResearch/hermes-agent/pull/73493)).
- Helped maintain the integration through Relay upgrades, provider compatibility fixes, native plugin adoption, and user documentation.

### NeMo Relay

- Built foundational pieces of Relay's dynamic-plugin system: the [control plane](https://github.com/NVIDIA/NeMo-Relay/pull/279), [configuration discovery](https://github.com/NVIDIA/NeMo-Relay/pull/290), [CLI lifecycle](https://github.com/NVIDIA/NeMo-Relay/pull/292), and [host policy and attestation](https://github.com/NVIDIA/NeMo-Relay/pull/302).
- Contributed the built-in [NeMo Guardrails backend](https://github.com/NVIDIA/NeMo-Relay/pull/197) and [PII-redaction plugin](https://github.com/NVIDIA/NeMo-Relay/pull/245).
- Turned upstream integration experience into reusable [framework-integration documentation](https://github.com/NVIDIA/NeMo-Relay/pull/707) and an [integration skill for solution architects and framework maintainers](https://github.com/NVIDIA/NeMo-Relay/pull/839).

### Across the agentic AI ecosystem

- Made target-specific system prompts follow routed and fallback model calls in [NeMo Switchyard](https://github.com/NVIDIA-NeMo/Switchyard/pull/464).
- Moved the NeMo Agent Toolkit profiler to an [ATIF-native trajectory pipeline](https://github.com/NVIDIA/NeMo-Agent-Toolkit/pull/1751).
- Added an experimental provider-neutral runtime identity contract with an [Okta reference for NemoClaw](https://github.com/NVIDIA/NemoClaw/pull/7265).
- Added an [Elasticsearch backend for cuVS-accelerated vector-search benchmarking](https://github.com/NVIDIA/cuvs/pull/1907).

## Ecosystem

**NVIDIA:** [NeMo Relay](https://github.com/NVIDIA/NeMo-Relay) · [NeMo Switchyard](https://github.com/NVIDIA-NeMo/Switchyard) · [OpenShell](https://github.com/NVIDIA/OpenShell) · [NeMoClaw](https://github.com/NVIDIA/NemoClaw) · [NeMo Agent Toolkit](https://github.com/NVIDIA/NeMo-Agent-Toolkit) · [NeMo Gym](https://github.com/NVIDIA-NeMo/Gym) · [cuVS](https://github.com/rapidsai/cuvs)

**Nous Research:** [Hermes Agent](https://github.com/NousResearch/hermes-agent)

During summer 2026, I was one of Hermes Agent's most active contributors while helping bring its native NeMo Relay integration into production.
