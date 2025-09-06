# Neural_Machine_Translation

• Built Transformer Language model, trained for 300 epochs on the WMT14 DE-EN dataset, achieving val. loss of  4.21 (multi-head) and 4.83 (single-head)

• Conducted ablation studies, showing long-range skips outperformed ( 4.02 val loss) short-range skips (4.16 val loss), which surpassed baseline multi-head

• Proposed novel distance-aware attention with token-distance bias, improving stability and translation accuracy by >18% over baseline multi-head model
