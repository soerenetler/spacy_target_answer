<!-- SPACY PROJECT: AUTO-GENERATED DOCS START (do not remove) -->

# 🪐 spaCy Project: transformer-based Target Answer Identification

Transformer based spacy model to identify possible answer sequences in the SQuAD or QUAC dataset

## 📋 project.yml

The [`project.yml`](project.yml) defines the data assets required by the
project, as well as the available commands and workflows. For details, see the
[spaCy projects documentation](https://spacy.io/usage/projects).

### ⏯ Commands

The following commands are defined by the project. They
can be executed using [`spacy project run [name]`](https://spacy.io/api/cli#project-run).
Commands are only re-run if their inputs have changed.

| Command | Description |
| --- | --- |
| `init-config` | Generate a default English NER config |
| `corpus` | Convert the data to spaCy's format |
| `train` | Train the full pipeline |
| `evaluate` | Evaluate on the test data and save the metrics |
| `clean` | Remove intermediate files |

### ⏭ Workflows

The following workflows are defined by the project. They
can be executed using [`spacy project run [name]`](https://spacy.io/api/cli#project-run)
and will run the specified commands in order. Commands are only re-run if their
inputs have changed.

| Workflow | Steps |
| --- | --- |
| `all` | `corpus` &rarr; `train` &rarr; `evaluate` |

### 🗂 Assets

The following assets are defined by the project. They can
be fetched by running [`spacy project assets`](https://spacy.io/api/cli#project-assets)
in the project directory.

| File | Source | Description |
| --- | --- | --- |
| `/content/gdrive/MyDrive/mt-qg-data/01_data/preprocessedData/quac/sentences_conll/dev.conll` | Local |  |

<!-- SPACY PROJECT: AUTO-GENERATED DOCS END (do not remove) -->
