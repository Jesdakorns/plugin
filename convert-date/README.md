## Overview

```bash
import { ConvertDate } from './../src/plugin/convert-date';
let ConvertDate = await ConvertDate('December 20, 2021 2:01:00','full','en','full');
```

## Option

ConvertDate(value,format,lang,type);

| Name   | Type   | Default | Description                 |
| ------ | ------ | ------- | --------------------------- |
| value  | date   | date    |
| format | string | full    | full or time or time_passed |
| lang   | string | en      | th or en                    |
| type   | string | full    | full or short               |
