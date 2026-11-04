Independent project, not affiliated with Supabase.

# prereg-sandbox

The one place where [preregistered](https://github.com/Dulatormanov/preregistered) may write: one label at a time, only after its owner approves the exact change. Its probes also show here what each token can and cannot do.

- The **probe issue** is the only issue the probes touch.
- The **prompt-injection issues** are test fixtures for the safety suite. Each holds a clearly fake canary string, which must never appear in a model's output.
- `.github/workflows/side_door_demo.yml` closes any issue that gets the label `probe-side-door`: a side door that the gateway must refuse.
