# Upstream audit

        - Paper anchor: Open Graph Benchmark: Datasets for Machine Learning on Graphs
        - Upstream repo: https://github.com/snap-stanford/ogb
        - Local clone: /Users/Rb/Documents/LLM based projects /sources/snap-stanford__ogb
        - Branch: master
        - Commit: 61e9784ca76edeaa6e259ba0f836099608ff0586
        - File count scanned: 264
        - Text files scanned: 208

        ## Strengths

        - Repository has a top-level README.

        ## Findings

        - No dedicated docs directory detected for architecture or operations guidance.
- No obvious tests directory or test files detected.
- No GitHub Actions workflow detected for repeatable checks.
- No container packaging signal detected, which makes demos and deployment less portable.
- No obvious Python dependency manifest was found.
- Mixed filename conventions detected: PascalCase, kebab-case, snake_case.
- Open maintenance markers detected: TODO in 7 file(s).
- Large files that may benefit from decomposition: examples/lsc/wikikg90m/dgl-ke-ogb-lsc/python/dglke/models/ke_model.py (978 lines), examples/lsc/wikikg90m/dgl-ke-ogb-lsc/python/dglke/dataloader/sampler.py (835 lines), examples/lsc/wikikg90m/dgl-ke-ogb-lsc/python/dglke/dataloader/KGDataset.py (789 lines).

        ## Dominant file types

        - `.py`: 168
- `.md`: 31
- `.png`: 21
- `.rst`: 15
- `<none>`: 8
- `.list`: 6
- `.yaml`: 4
- `.csv`: 3

        ## Maintenance markers

        - TODO: examples/lsc/wikikg90m/dgl-ke-ogb-lsc/python/dglke/models/ke_model.py, examples/lsc/wikikg90m/dgl-ke-ogb-lsc/python/dglke/models/general_models.py, examples/lsc/wikikg90m/dgl-ke-ogb-lsc/python/dglke/models/mxnet/score_fun.py, examples/lsc/wikikg90m/dgl-ke-ogb-lsc/python/dglke/models/mxnet/tensor_models.py, examples/lsc/wikikg90m/dgl-ke-ogb-lsc/python/dglke/models/pytorch/ke_tensor.py, examples/lsc/wikikg90m/dgl-ke-ogb-lsc/python/dglke/models/pytorch/score_fun.py, examples/lsc/wikikg90m/dgl-ke-ogb-lsc/python/dglke/models/pytorch/tensor_models.py
