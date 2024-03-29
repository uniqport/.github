### Uniqport Cloud Tools
A set of basic cloud tools written in Golang aims to be used in development environments to emulate production at the infrastructure level. <br>

----

Roadmap: <br>

- [ ] 🟡 **utils**: Utilities that will be mainly used in the other uniqport cloud tools. Such as TCP / WebSocket / dependency injection mediators. 
- [ ] 🔴 **vim-client**: a VIM (Virtual Infrastructure Manager) cli for easily managing virtual infrastructure resources, and simplifying tasks like creating, starting, stopping, and monitoring virtual servers. 🔴
- [ ] 🔴 **virtualization-manager**: Repository for the server-side component responsible for managing the virtual infrastructure, serving as the counterpart to the VIM client.
- [ ] 🔴 **hypervisor**:  Responsible for managing and orchestrating virtual server instances
- [ ] 🔴 **virtual-server**: Individual instances running within the hypervisor.
- [ ] 🔴 **message-broker**: Handling centralized communication and message passing between components.
- [ ] 🔴 **reverse-proxy**: Routing incoming requests to appropriate destinations.
- [ ] 🔴 **load-balancer**: Distributor of the incoming requests across multiple virtual servers.
- [ ] 🔴 **monitoring**: monitoring and health-checking system, responsible for detecting failures and managing system health
- [ ] 🔴 **Architect**: Serves as the central repository housing the comprehensive implementation of the uniqport cloud tools, facilitating the seamless deployment of complete cloud infrastructure. It acts as the primary tool for deploying the VIM or virtualization manager onto servers.

----
_These tools mainly serve the purpose of understanding, learning, and creating a cloud infrastructure, not mainly to be used in production. Feel free to contribute, create issues, or open a discussion for your questions_

-------
<small>_Maintainer(s): [kaandesu](https://github.com/kaandesu)_</small> 
