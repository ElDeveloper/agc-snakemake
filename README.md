Snakemake Tutorial Deployed in AGC
==================================

```bash
# assuming you have an active account
agc context deploy --context spotContext
agc workflow run snakemake-tutorial --context spotContext
agc logs engine --context spotContext -t
```
