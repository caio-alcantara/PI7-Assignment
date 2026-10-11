# Assignment PI7 – ZM002 Artificial Intelligence - Caio de Alcantara Santos

Assignments for the AI minor at Zuyd University of Applied Sciences. Each assignment is a
self-contained Jupyter notebook with the research, the code and the evaluation.

| Folder | Assignment |
|---|---|
| `A1/` | Evolutionary algorithms – colouring the map of Europe with a genetic algorithm |
| `A2/` | Neural networks – recognising spoken elevator commands with a CNN (mini speech commands dataset) |
| `A3/` | Auto-encoders and variational auto-encoders (to do) |

## How to run

Each assignment folder has its own `requirements.txt`. Example for A1:

```bash
cd A1
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook
```

Then open the `.ipynb` file in the folder and run the cells from top to bottom.

In VS Code, open the notebook and select the interpreter from `.venv` as the kernel.

### Notes for A2

- The dataset (`mini_speech_commands/`, ~250 MB) is not in the repository. The notebook downloads it
  automatically on the first run if the folder is missing.
- Running the whole notebook takes about 30 minutes on a laptop CPU, because section 6 trains every
  configuration three times.
- The live microphone demo in section 7.3 is off by default; set `LIVE_DEMO = True` to use it.
