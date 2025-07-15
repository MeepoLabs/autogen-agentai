Welcome to autogen-agentai's documentation!
===================================

.. image:: https://img.shields.io/pypi/v/autogen-agentai.svg
   :target: https://pypi.org/project/autogen-agentai/
   :alt: PyPI version

.. image:: https://img.shields.io/pypi/pyversions/autogen-agentai.svg
   :target: https://pypi.org/project/autogen-agentai/
   :alt: Python versions

.. image:: https://img.shields.io/github/license/meepolabs/autogen-agentai.svg
   :target: https://github.com/meepolabs/autogen-agentai/blob/main/LICENSE
   :alt: License

.. image:: https://readthedocs.org/projects/autogen-agentai/badge/?version=latest
   :target: https://autogen-agentai.readthedocs.io/en/latest/?badge=latest
   :alt: Documentation Status

.. warning::
   **Development Status**: Development of this repository is currently paused while we build the foundational `pyagentai <https://github.com/MeepoLabs/pyagentai>`_ library. Once pyagentai is complete, we will resume development of this AutoGen adapter.

An extension for Microsoft AutoGen that allows running agents from agent.ai.

Overview
--------

autogen-agentai is a Python package that serves as an extension for Microsoft's AutoGen framework, enabling the use of agent.ai agents within AutoGen workflows. This library will serve as an adapter between AutoGen and the `pyagentai <https://github.com/MeepoLabs/pyagentai>`_ library.

**Architecture Overview:**

- **pyagentai**: Core library for interacting with the agent.ai platform
- **autogen-agentai**: AutoGen adapter that uses pyagentai to integrate agent.ai agents into AutoGen workflows

Once complete, this package will enable developers to:

- **Agent Integration**: Seamlessly integrate agent.ai agents into AutoGen workflows using the pyagentai library
- **Agent Communication**: Enable communication between AutoGen agents and agent.ai agents
- **Simplified API**: Provide a simple interface to configure and use agent.ai services through AutoGen
- **Extensibility**: Extend AutoGen's capabilities with agent.ai's specialized AI agents

Key Features (Planned)
----------------------

Agent Interoperability
~~~~~~~~~~~~~~~~~~~~~~~~~~~

- Connect AutoGen's agent ecosystem with agent.ai's specialized agents
- Enable cross-platform agent communication
- Maintain agent context across different platforms
- Synchronize agent states and knowledge

Configuration Management
~~~~~~~~~~~~~~~~~~~~~~~~~

- Simple configuration for agent.ai API connections
- Credential management for agent.ai services
- Environment-based configuration options
- Persistent configuration storage

Workflow Integration
~~~~~~~~~~~~~~~~~~~~

- Integrate agent.ai agents into existing AutoGen workflows
- Create hybrid workflows combining agents from both platforms
- Enable task delegation between different agent types
- Support for complex multi-agent scenarios

Developer Tools
~~~~~~~~~~~~~~~

- Debugging utilities for agent interactions
- Logging and monitoring capabilities
- Testing utilities for agent.ai integration
- Documentation and examples

.. toctree::
   :maxdepth: 2
   :caption: Contents:

   installation
   core_concepts
   getting_started

Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
