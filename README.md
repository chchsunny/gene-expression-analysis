#  Gene Expression Analysis Project

本專案使用 Python 進行基因表現資料的差異分析與視覺化，並透過互動式介面（Google Colab）讓使用者能即時選擇基因並檢視 boxplot 圖。

---

##  features

| `gene_analysis.ipynb` | 主要分析流程（支援互動式選單） |
| `RNA_expression_mock_data.csv` | 原始基因表現資料 |
| `differential_expression_results.csv` | 所有基因的 log2FC 與 p-value 統計結果 |
| `significant_genes.csv` | 篩選條件（log2FC > 1 且 p < 0.05）下的顯著基因 |
| `heatmap.png` | 顯示基因的熱圖 |
| `volcano_plot.png` | 火山圖：顯示顯著性與表現量變化 |

---

##  start up

點擊下方按鈕，即可在 Colab 中互動式執行分析程式：

markdown<br>[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/chchsunny/gene-expression-analysis/blob/main/gene_analysis.ipynb)<br>

---

##  results

###  Volcano Plot
![Volcano Plot](volcano_plot.png)

### Heatmap
![Heatmap](heatmap.png)

---

## License

本專案使用 MIT License 授權，歡迎自由使用與參考
