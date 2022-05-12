Snakemake workflow with AGC
===========================

```bash
# assuming you have an active account
agc context deploy --context spotContext
agc workflow run snakemake-tutorial --context spotContext
agc logs engine --context spotContext -t -r .....
```
