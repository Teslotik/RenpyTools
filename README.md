# Renpy tools

Collection of tools we use for our visual novels.

## Drawio to rpy

Convert drawio diagram to a single rpy file with FSTM class and all transitions.

To make diagram in DrawIO

- add block and write a label inside it

- to make transition, connect blocks with an arrow

- to make condition, add statement inside arrow

    - write a python condition to choose between next blocks based on variables

    - write a text to make a choice

    - if condition is ambiguous, use $ sign to make it a python condition

Use the folowing command to install

```
python -m pip install lxml
```

To generate rpy use this

```
python script.py mydiagram.drawio
```