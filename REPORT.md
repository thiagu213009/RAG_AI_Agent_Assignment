# Modified Modules

1. rag_agent.py - Changed a prompt to act as a "Coding Assistant" as per Assignment
2. ingestion.py - Switched to **STRATEGY 3** (TokenTextSplitter) with `chunk_size=200` tokens and `chunk_overlap=50` tokens
    # Better for LLMs since they process tokens, not characters.
    # Less overlap (0-100)   = less redundancy, but may miss split sentences
    # Smaller (300-500)      = more precise retrieval, but may lose context
3. rag_agent.py - Changed `TEMPERATURE` to `0.2` for bit more creative code suggestions
4. Example Queries Used:
    # What is mean by GUI Controller and what it is used for?
    # Can you please explain period frequency conversion with examples?
    # I am finding difficulty on understanding concept of Transposing Arrays and Swapping Axes? Please help on it
    # When do we use quaterly period frequencies?

