import pypandoc

readme = """# Hi, I'm Varshini 👋

**AI & ML Engineer | Python | Machine Learning | Agentic AI**

I'm a final-year B.Tech Artificial Intelligence and Machine Learning student interested in building practical AI applications and intelligent systems.

My interests include machine learning, deep learning, natural language processing, Generative AI, and multi-agent systems. I enjoy learning by building projects and solving real-world problems through technology.

## Technical Skills

- **Programming:** Python
- **AI & Machine Learning:** Machine Learning, Deep Learning, NLP, Generative AI
- **AI Application Development:** LangChain, FAISS, Retrieval-Augmented Generation (RAG), Multi-Agent Systems
- **Development Tools:** Git, GitHub, VS Code, Streamlit, Flask
- **Core Concepts:** Data Structures, Object-Oriented Programming, DBMS

## Featured Projects

### [SchemeSaathi — Government Scheme Eligibility Assistant](https://github.com/varshini-2005-prog/SchemeSaathi-Agentic-AI-Based-Government-Scheme-Eligibility-Assistant)

A multilingual AI assistant designed to guide users through government scheme eligibility using adaptive questions, official scheme documents, and rule-based evaluation.

### [SkillForge AI — Multi-Agent Interview Preparation Platform](https://github.com/varshini-2005-prog/skillforge-ai)

An AI-powered interview preparation platform using retrieval-augmented generation, FAISS, and specialized agents to support DSA learning and technical interview practice.

### [Smart Geo-Fencing Alert System](https://github.com/varshini-2005-prog/SMART_GEO_FENCING)

A location-based application designed to detect geofence entry and exit events and send SMS alerts.

## Currently Learning

- Agentic AI and LLM application development
- Data Structures and Algorithms
- Building reliable and maintainable AI applications

## Career Goal

To grow as an AI & ML Engineer by developing practical, reliable, and impactful intelligent applications.

## Connect

- **GitHub:** [varshini-2005-prog](https://github.com/varshini-2005-prog)
- **LinkedIn:** Add your LinkedIn profile URL here

---

*Continuous learning. Practical building. Meaningful impact.*
"""

output_path = "/mnt/data/README.md"
pypandoc.convert_text(readme, "md", format="md", outputfile=output_path, extra_args=["--standalone"])
print(f"Created {output_path}")
