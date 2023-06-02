## Basics
- Use **three or more hyphens** (---) to separate table header from table content
- Use pipe (|) to separate table columns

E.g. the following table

| Name  | Job    |
| ----- | ------ |
| Alice | Doctor |
| Bob   | Nurse  |

is give by the following markdown code:
```
| Name  | Job    |
| ----- | ------ |
| Alice | Doctor |
| Bob   | Nurse  |
```

The alignment in markdown text is quite flexible. As long as it's understandable by
markdown engine, you do not have to make the raw text unnecessarily beautiful. For instance,
the following is equivalent to the above
```
| Name | Job |
| --- | --- |
| Alice | Doctor |
| Bob | Nurse |
```


## Align Text to The Left/Right/Middle in A Cell
Use the colon character (:) to indicate! E.g.
```
| Name | Job | Income (USD/year) |
| :---: | :--- | ---: |
| Alice | Doctor | 50,000 |
| Bob | Nurse | 200,000 |
```

gives
| Name | Job | Income (USD/year) |
| :---: | :--- | ---: |
| Alice | Doctor | 50,000 |
| Bob | Nurse | 200,000 |
