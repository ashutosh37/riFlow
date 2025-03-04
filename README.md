

# riFlow - Secure Workflow Automation for Technical Teams

riFlow is a workflow automation platform that gives technical teams the flexibility of code with the speed of no-code. With 400+ integrations, native AI capabilities, and a fair-code license, riFlow lets you build powerful automations while maintaining full control over your data and deployments.

![riFlow.io - Screenshot](https://raw.githubusercontent.com/riFlow-io/riFlow/master/assets/riFlow-screenshot-readme.png)

## Key Capabilities

- **Code When You Need It**: Write JavaScript/Python, add npm packages, or use the visual interface
- **AI-Native Platform**: Build AI agent workflows based on LangChain with your own data and models
- **Full Control**: Self-host with our fair-code license or use our [cloud offering](https://app.riFlow.cloud/login)
- **Enterprise-Ready**: Advanced permissions, SSO, and air-gapped deployments
- **Active Community**: 400+ integrations and 900+ ready-to-use [templates](https://riFlow.io/workflows)

## Quick Start

Try riFlow instantly with [npx](https://docs.riFlow.io/hosting/installation/npm/) (requires [Node.js](https://nodejs.org/en/)):

```
npx riFlow
```

Or deploy with [Docker](https://docs.riFlow.io/hosting/installation/docker/):

```
docker volume create riFlow_data
docker run -it --rm --name riFlow -p 5678:5678 -v riFlow_data:/home/node/.riFlow docker.riFlow.io/riFlowio/riFlow
```

Access the editor at http://localhost:5678

## Resources

- 📚 [Documentation](https://docs.riFlow.io)
- 🔧 [400+ Integrations](https://riFlow.io/integrations)
- 💡 [Example Workflows](https://riFlow.io/workflows)
- 🤖 [AI & LangChain Guide](https://docs.riFlow.io/langchain/)
- 👥 [Community Forum](https://community.riFlow.io)
- 📖 [Community Tutorials](https://community.riFlow.io/c/tutorials/28)

## Support

Need help? Our community forum is the place to get support and connect with other users:
[community.riFlow.io](https://community.riFlow.io)

## License

riFlow is [fair-code](https://faircode.io) distributed under the [Sustainable Use License](https://github.com/riFlow-io/riFlow/blob/master/LICENSE.md) and [riFlow Enterprise License](https://github.com/riFlow-io/riFlow/blob/master/LICENSE_EE.md).

- **Source Available**: Always visible source code
- **Self-Hostable**: Deploy anywhere
- **Extensible**: Add your own nodes and functionality

[Enterprise licenses](mailto:license@riFlow.io) available for additional features and support.

Additional information about the license model can be found in the [docs](https://docs.riFlow.io/reference/license/).

## Contributing

Found a bug 🐛 or have a feature idea ✨? Check our [Contributing Guide](https://github.com/riFlow-io/riFlow/blob/master/CONTRIBUTING.md) to get started.

## Join the Team

Want to shape the future of automation? Check out our [job posts](https://riFlow.io/careers) and join our team!

## What does riFlow mean?

**Short answer:** It means "nodemation" and is pronounced as n-eight-n.

**Long answer:** "I get that question quite often (more often than I expected) so I decided it is probably best to answer it here. While looking for a good name for the project with a free domain I realized very quickly that all the good ones I could think of were already taken. So, in the end, I chose nodemation. 'node-' in the sense that it uses a Node-View and that it uses Node.js and '-mation' for 'automation' which is what the project is supposed to help with. However, I did not like how long the name was and I could not imagine writing something that long every time in the CLI. That is when I then ended up on 'riFlow'." - **Jan Oberhauser, Founder and CEO, riFlow.io**
