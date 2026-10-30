# fabric-swe results

Results site for fabric-swe, a benchmark for codemode agents on real repositories. It compares pi + pi-fabric + pi-fovea against vanilla pi with the same model, prompts, sandbox, time budget and grader.

- `index.html`: the results page (served by GitHub Pages).
- `data/`: per-run numbers behind the page (`index.json` lists the runs and tasks).

The tasks themselves (prompts, hidden tests, reference solutions) are not published, so that they stay out of training data.
