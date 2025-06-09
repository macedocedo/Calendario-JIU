# https://macedocedo.github.io/Calendario-JIU/


# 📅 Calendário de Treinos

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

## ✨ Funcionalidades Principais

| Funcionalidade | Descrição |
|---------------|-----------|
| **Seleção de Períodos** | Defina intervalos de datas clicando no calendário ou usando campos de data |
| **Visualização por Mês** | Navegação entre meses com botões ou gestos de swipe (mobile) |
| **Gestão de Dias de Treino** | Marque quais dias da semana serão de treino |
| **Estatísticas** | Visualize total de dias e quantos serão de treino |
| **Armazenamento Local** | Seus períodos são salvos no navegador (LocalStorage) |
| **Exportação de Dados** | Exporte para CSV ou JSON |

## 🚀 Como Usar

1. Acesse o aplicativo [aqui](#) *(link para sua página)*
2. Selecione as datas inicial e final
3. Escolha os dias de treino
4. Adicione informações adicionais (opcional)
5. Clique em "Salvar Período"

```javascript
// Exemplo de estrutura de dados armazenada
{
  startDate: "2023-01-01",
  endDate: "2023-01-31",
  beltGrade: "Faixa Azul",
  trainingDays: ["1", "3", "5"], // Seg, Qua, Sex
  notes: "Treino para competição"
}
