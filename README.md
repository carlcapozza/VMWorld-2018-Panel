# VMWorld Panel discussion

## Title : vSphere and Ansible: A panel discussion of lessons learned, tips and tricks

## Key Takeaways:

Learn from panelist experiences using Ansible to manage vSphere environments.

Learn about limitations, workarounds and use cases.

Understand how you can integrate Ansible into your enterprise operations.

Gain insight from people who were first VMware administrators and have now embraced Ansible.

## Session Abstract:

The IT industry is pushing to adapt automation. For VMware environments, there has been a strong push to use API calls, particularly RESTful APIs. Once a vSphere administrator understands what interacting with an API entails, the question becomes - how does this make my life easier? Ansible is one tool that has gained popularity as the DevOps community grows. 


## Extended Abstract:

Ansible is a flexible, highly readable, configuration management tool, which helps administrators consistently deploy and manage an every growing infrastructure. 


However, the fact is that Ansible is an open source project, with a 3rd party support structure. VMware supports the APIs, but sadly it's very difficult to extend support to customers using a 3rd party tool to interact with them. The Ansible community has made available several modules, but most were built using Python SDK interactions and last tested on vSphere 5.5, and some of them are still in "preview" mode. The modern way of using Ansible and vSphere is with HTTP/S calls to the RESTful API, and that has it's own set of limitations.

Come join a panel where a VMware customer interviews industry veterans on how they have interacted with vSphere and Ansible 