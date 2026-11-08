# LVCN — Laboratório Virtual de Cálculo Numérico

Aplicação educacional em Streamlit para estudar métodos numéricos de determinação de raízes de funções.

## Recursos
- Funções predefinidas com preenchimento automático de f(x), a, b e x₀.
- Função personalizada.
- Análise dos sinais de f(a), f(b) e f(m).
- Tabelas completas das iterações.
- Gráfico interativo da função com zoom, hover e visualização de iterações.
- Gráfico da progressão do erro em escala logarítmica.
- Visualização da reta tangente de Newton-Raphson.
- Exportação das tabelas em CSV.

## Executar localmente
```bash
pip install -r requirements.txt
streamlit run app.py
```

## Publicar
Envie app.py, requirements.txt e README.md para a raiz do repositório GitHub conectado ao Streamlit Community Cloud. O aplicativo principal é app.py.
