# 🔍 Explorando Content Filters da Azure OpenAI  

Este repositório contém um projeto prático desenvolvido durante o curso de Inteligência Artificial da Azure na DIO. O objetivo deste projeto é explorar os **filtros de conteúdo** disponíveis na **Azure OpenAI**, garantindo que os modelos de IA gerem respostas seguras e adequadas para diferentes contextos.  

## Objetivo  

Compreender e testar os diferentes **níveis de filtragem** oferecidos pela Azure OpenAI para moderação de conteúdo, analisando como a IA pode bloquear ou ajustar respostas com base em regras predefinidas.  

---

## 📌 Estrutura do Projeto  

📂 `output/` - Contém prints e resultados dos testes realizados.  
📄 `README.md` - Documentação do projeto, insights e aprendizados.  

---

## 🚀 Passo a Passo do Processo  

### 1️⃣ Configuração dos Content Filters  
- Utilizamos a API da Azure OpenAI para testar diferentes **níveis de bloqueio**:  
  - **Baixo**: Permite a maioria dos conteúdos.  
  - **Moderado**: Filtra conteúdos sensíveis.  
  - **Alto**: Bloqueia quase todo conteúdo potencialmente problemático.  

### 2️⃣ Testes de Geração de Texto  
- Enviamos diferentes solicitações para o modelo **GPT-4 da Azure OpenAI**, avaliando como cada filtro afeta a resposta gerada.  
- Exemplos de testes realizados:  
  - Perguntas sobre tópicos sensíveis (violência, discriminação, conteúdos explícitos).  
  - Solicitações para geração de fake news ou informações enganosas.  
  - Testes com palavras neutras para avaliar o impacto dos filtros.  

## 📸 Exemplos e Resultados  

### 🎙️ Exemplo de resposta com e sem definição instruções e contexto ao modelo
Respostas obtidas:  
![Resultado](output/image-generative.png)  


---

## 📊 Insights e Possibilidades  

✅ **Moderação Automatizada**  
Os filtros de conteúdo da Azure OpenAI ajudam a evitar respostas inadequadas sem necessidade de intervenção humana.  

✅ **Aprimoramento de Assistentes Virtuais**  
Bots e assistentes podem utilizar os filtros para garantir interações seguras e alinhadas com políticas organizacionais.  

✅ **Conformidade com Regulamentações**  
Empresas podem usar os filtros para garantir que a IA siga normas como GDPR e LGPD ao evitar informações sensíveis.  

✅ **Customização dos Níveis de Segurança**  
Os filtros permitem ajustar a severidade do bloqueio de acordo com a necessidade do negócio.  

---

## 🔗 Links Úteis  

- [Laboratório de IA Generativa](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/12-generative-ai.html)  
- [Laboratório de Azure OpenAI](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/13-azure-openai.html)  
- [Laboratório de Content Filters da Azure OpenAI](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/14-azure-openai-content-filters.html)

