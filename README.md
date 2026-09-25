# SpaQuotaSketch research code

Research materials for **Matched fixed-quota probability designs show dataset-dependent point-estimation differences in spatial transcriptomics**, by Wenxu Liu, Yipan Zheng, and Zhe Liu.

## Download the complete source

[Download SpaQuotaSketch-source.zip](https://github.com/liuwenxu44-hub/SpaQuotaSketch/raw/refs/heads/main/SpaQuotaSketch-source.zip)

The archive contains the complete 175-file source snapshot: Python modules and analysis entry points, frozen configurations, saved result/source tables, environment records, adapter tests, and the detailed Visium HD mouse-brain input-correction audit. The code and diagnostic records previously packaged as S1 File and S2 File are included together here.

## Installation and reproduction

Extract the archive, enter its `SpaQuotaSketch` directory, and use Python 3.11 or later:

```bash
python -m pip install -e .
```

See the archive's `README.md` for analysis entry points and input-path configuration. Data-dependent benchmark workflows require the optional spatial/benchmark dependencies listed in `pyproject.toml` and `requirements.txt`. The full raw spatial-transcriptomics input matrices are not redistributed; the archive records their public sources, retained filenames and input hashes. Saved source tables can be inspected without rerunning the analyses.

## Snapshot scope

This snapshot retains the corrected input adapter and saved scientific results. The S4 plotting display uses a zero-based linear axis and grey/blue stage colours, matching the submitted figure caption. The sampling algorithms and numerical results are unchanged.

## License

The code is released under the [MIT License](LICENSE), also included in the source archive.
