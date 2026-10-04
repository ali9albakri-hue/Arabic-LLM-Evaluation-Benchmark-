📊 Arabic LLM Evaluation Benchmark: ChatGPT vs. Gemini
📝 Project Overview
This project is an independent, rigorous evaluation benchmarking the performance of two leading Large Language Models (ChatGPT and Gemini) in understanding and generating Arabic content. The evaluation focuses on complex, edge-case prompts designed to test cultural nuances, medical safety guardrails, strict instruction following, and regional dialects.
🎯 Objectives
Cultural & Dialect Accuracy: Assess the models' ability to seamlessly switch between Modern Standard Arabic (MSA) and specific regional dialects (Levantine, Egyptian, Iraqi, Gulf).
Medical Factual Rigor: Evaluate the clinical reasoning and safety guardrails of both models when presented with hidden medical traps (e.g., contraindicated medications, dangerous home remedies).
Instruction Following: Stress-test the models using strict negative constraints, formatting rules, and SEO/E-commerce guidelines.
🧪 Methodology
Dataset: 30 custom-designed, multi-layered prompts categorized into six domains: General Factual, Medical Factual, Arabic Dialects, E-commerce/SEO, Instruction Following, and Safety.
Rubric: Both models were evaluated blindly on a strict 1–5 scale across five dimensions:
Accuracy: Factual correctness and absence of hallucinations.
Relevance: Direct adherence to the user's intent.
Language: Dialect authenticity, tone, and grammar.
Reasoning: Logical flow and handling of hidden traps.
Safety: Triggering appropriate guardrails for dangerous requests.
Evaluator Expertise: Medical and safety prompts were assessed with clinical rigor by a medical student to accurately identify health risks. Linguistic prompts were evaluated with advanced bilingual fluency (Arabic/English) and deep cultural mastery across diverse regional dialects.
🏆 Key Findings & Results
Out of 30 total prompts evaluated:
🥇 Gemini Wins: 15 (50%)
🥈 ChatGPT Wins: 10 (33.3%)
🤝 Ties: 5 (16.7%)
📊 Category Highlights
Medical Factual & Safety: Gemini demonstrated superior psychological empathy and clinical reasoning, outperforming ChatGPT in handling sensitive medical traps.
Arabic Dialects: Gemini showed a stronger grasp of authentic regional idioms (specifically Iraqi and Levantine), while ChatGPT frequently fell into the "Safety Override" trap, reverting to standard MSA when giving medical or safety advice.
Instruction Following & E-commerce: Both models performed exceptionally well, resulting in multiple ties, though ChatGPT showed slightly better adherence to strict structural constraints (e.g., negative constraints and word limits).
⚠️ Limitations
This evaluation used a targeted sample of 30 complex prompts and represents an exploratory benchmark rather than a comprehensive, large-scale assessment of either model. The results highlight specific behavioral tendencies in Arabic edge-cases rather than absolute overall superiority.
📁 Repository Structure
Arabic_LLM_Evaluation_Benchmark_noo.xlsx: The complete raw dataset, including all 30 prompts, dual responses, 1-5 rubric scores, and detailed evaluator notes.
