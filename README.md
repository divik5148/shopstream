# ShopStream

Multi-agent customer support for a fictional retailer. Specialized agents look up orders, retrieve return/shipping/warranty policy, decide refund eligibility, and draft the customer reply.

Built with Amazon Bedrock AgentCore, the Strands Agents SDK, and S3 Vectors. Runtime deployment uses **AgentCore CLI 0.30.0**.

## Getting started

Setup, deploy, and usage are in the [project README](starter/README.md). The implementation lives in `starter/src/agent_orchestrator.py`. Create and sync the three Knowledge Bases before a full deploy. The optional Lambda-backed gateway is not required.

## License

[License](../LICENSE.md)
