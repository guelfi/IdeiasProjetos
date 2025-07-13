As an expert in market analysis and product strategy for Micro SaaS, your task is to analyze a list of Micro SaaS ideas, conduct market research for each, and provide an assessment of their success potential.

**Context:**
You will be provided with the HTML content of a file listing 20 Micro SaaS ideas. Each idea includes a description and technical requirements. Please consider this HTML content as the primary source for the ideas.

**Objective:**
For EACH Micro SaaS idea presented in the provided HTML content, you must:

1.  **Identify Similar Products/Competitors:** Search the internet for existing products or services that are similar or direct competitors to the idea. List at least 3-5 examples, if possible.
2.  **Analyze Competition:**
    *   What is the market saturation level for this idea? (Low, Medium, High)
    *   What are the main differentiators of existing competitors?
    *   Are there any unexplored niches or opportunities that a new Micro SaaS could focus on?
3.  **Evaluate Success Potential:**
    *   Assign a "Success Potential" for creating a new Micro SaaS in this area, considering competition and opportunities. Use the following scale:
        *   **Very Low:** Saturated market, difficult differentiation, low demand.
        *   **Low:** Market with many strong competitors, but some niche opportunities.
        *   **Medium:** Market with competition, but room for innovation or specific niches.
        *   **High:** Market with growing demand, moderate competition, or clear differentiation opportunities.
        *   **Very High:** Emerging market, low competition, and high demand.
    *   Justify your assessment, explaining the factors contributing to this potential (demand, differentiation, ease of entry, etc.).

**Output Format:**
Your response MUST be in **Brazilian Portuguese**. For each idea, present the analysis in the following HTML snippet format, which can be directly inserted into the `ideias.html` file. Ensure the HTML is well-formed and uses the `idea-analysis` class for styling.

```html
<div class="idea-analysis">
    <h4>Análise de Mercado e Potencial de Sucesso</h4>
    <p><strong>Produtos Semelhantes/Concorrentes:</strong></p>
    <ul>
        <li>[Nome do Concorrente 1] - [Breve descrição/foco]</li>
        <li>[Nome do Concorrente 2] - [Breve descrição/foco]</li>
        <li>[Nome do Concorrente 3] - [Breve descrição/foco]</li>
        <!-- Adicione mais se encontrar -->
    </ul>
    <p><strong>Análise da Concorrência:</strong></p>
    <ul>
        <li>Nível de Saturação: [Baixo/Médio/Alto]</li>
        <li>Diferenciais dos Concorrentes: [Pontos fortes comuns ou únicos]</li>
        <li>Oportunidades de Nicho/Diferenciação: [Sugestões de como a nova Micro SaaS pode se destacar]</li>
    </ul>
    <p><strong>Potencial de Sucesso:</strong> [Muito Baixo/Baixo/Médio/Alto/Muito Alto]</p>
    <p><strong>Justificativa:</strong> [Explicação detalhada do porquê desse potencial, considerando demanda, concorrência, inovação, etc.]</p>
</div>
```

**Important Note for the User:**
After this prompt, you should paste the *entire HTML content* of your `ideias.html` file into the AI tool.