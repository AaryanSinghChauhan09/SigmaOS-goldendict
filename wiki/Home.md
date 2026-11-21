# SigmaOS-goldendict

SigmaOS integration component for **GoldenDict dictionary**.

## Commands

```bash
sigmaos-goldendict install   # install package + deploy defaults
sigmaos-goldendict deploy    # copy config templates to $HOME
sigmaos-goldendict status    # binary/package/config report
sigmaos-goldendict reset     # remove deployed config
sigmaos-goldendict open      # launch the application
```

## Design

- Shell-based component manager (Omarchy-style per-app repos)
- Secure defaults; no secrets stored
- Deterministic `test.sh` with isolated `$HOME`
