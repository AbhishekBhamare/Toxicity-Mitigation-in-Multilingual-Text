# Evaluation Metrics

## Model Performance Summary

| Metric | Score | Description |
|--------|-------|-------------|
| **BLEU Score** | `0.4511` | Measures n-gram overlap between generated and reference text |
| **ROUGE-1 F1** | `0.3014` | Unigram overlap between generated and reference summaries |
| **ROUGE-2 F1** | `0.2481` | Bigram overlap between generated and reference summaries |
| **ROUGE-L F1** | `0.3003` | Longest common subsequence based evaluation |
| **Semantic Similarity** | `0.9439` | Cosine similarity between sentence embeddings |
| **Sentiment Score** | `0.2120` | Sentiment polarity score (-1 to 1 range) |
| **Fluency (Perplexity)** | `253.31` | Language model perplexity (lower is better) |

---

## 📊 Performance Breakdown

### Translation Quality
- **BLEU Score**: `45.11%` - Good translation quality with moderate n-gram overlap

### Summary Quality  
- **ROUGE-1**: `30.14%` - Reasonable word-level overlap
- **ROUGE-2**: `24.81%` - Good phrase-level coherence
- **ROUGE-L**: `30.03%` - Consistent structural similarity

### Semantic Understanding
- **Semantic Similarity**: `94.39%` - Excellent semantic preservation

### Text Characteristics
- **Sentiment**: `0.21` - Slightly positive sentiment
- **Fluency**: `253.31` - Moderate fluency (room for improvement)

---

## 🎯 Key Insights

| ✅ **Strengths** | ⚠️ **Areas for Improvement** |
|------------------|------------------------------|
| High semantic similarity (94.39%) | ROUGE scores could be higher |
| Decent BLEU performance | Fluency needs optimization |
| Consistent cross-metric performance | Sentiment analysis refinement |

---

## 📈 Benchmarking

```
Semantic Similarity  ████████████████████████████████████████ 94.39%
BLEU Score          ██████████████████████████████           45.11%
ROUGE-1 F1          ████████████████████                     30.14%
ROUGE-L F1          ████████████████████                     30.03%
ROUGE-2 F1          ████████████████                         24.81%
Sentiment Score     ████████                                 21.20%
```

---
