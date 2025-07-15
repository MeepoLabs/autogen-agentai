Getting Started
===============

.. warning::
   **Development Status**: Development of this repository is currently paused while we build the foundational `pyagentai <https://github.com/MeepoLabs/pyagentai>`_ library. Once pyagentai is complete, we will resume development of this AutoGen adapter.

This guide will help you get started with autogen-agentai once it becomes available.

Installation (Future)
---------------------

Once available, you will be able to install autogen-agentai using pip:

.. code-block:: bash

    pip install autogen-agentai

Or using Poetry:

.. code-block:: bash

    poetry add autogen-agentai

Basic Usage (Planned)
--------------------

Here's a planned example of how autogen-agentai will work to connect to agent.ai:

.. code-block:: python

    from autogen_agentai import AgentAIExtension
    import autogen

    # Initialize the extension with your agent.ai API key
    # This will use the pyagentai library under the hood
    agentai_extension = AgentAIExtension(api_key="your_agentai_api_key")

    # Create an AutoGen agent with agent.ai capabilities
    assistant = autogen.AssistantAgent(
        name="assistant",
        llm_config={"config_key": "config_value"},
        extensions=[agentai_extension]
    )

    # Use the agent normally in AutoGen workflows
    # The agent will have access to agent.ai capabilities through pyagentai

Architecture
-----------

autogen-agentai will be built as an adapter that uses the `pyagentai <https://github.com/MeepoLabs/pyagentai>`_ library:

- **pyagentai**: Handles all direct interactions with the agent.ai platform
- **autogen-agentai**: Provides the AutoGen integration layer using pyagentai

    # Now your agent has access to agent.ai capabilities

Next Steps
----------

- Learn about :doc:`core_concepts`
