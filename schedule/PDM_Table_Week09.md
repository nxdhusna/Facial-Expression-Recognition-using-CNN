# Precedence Diagram Method (PDM) Table

| Activity | Duration | Predecessors | ES (Early Start) | EF (Early Finish) | LS (Late Start) | LF (Late Finish) | Slack (LS - ES) |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| **A** | 2 | — | 0 | 2 | 0 | 2 | 0 |
| **B** | 3 | A | 2 | 5 | 2 | 5 | 0 |
| **C** | 4 | B | 5 | 9 | 5 | 9 | 0 |
| **D** | 3 | A | 2 | 5 | 6 | 9 | 4 |
| **E** | 6 | C, D | 9 | 15 | 9 | 15 | 0 |
| **F** | 3 | E | 15 | 18 | 15 | 18 | 0 |
| **G** | 5 | D | 5 | 10 | 13 | 18 | 8 |
| **H** | 2 | F, G | 18 | 20 | 18 | 20 | 0 |
| **I** | 4 | H | 20 | 24 | 20 | 24 | 0 |
