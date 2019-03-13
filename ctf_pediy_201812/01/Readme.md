# Windows 64 Program

 - System requirement: Chinese Version Windows 7 64-bit

```c
  v9 = GetDlgItemTextA(v5, 1000, &String, 81);
  GetDlgItemTextA(v5, 1000, &Dst, 101);
  if ( v9 != '\x06' || Dst != '6' || v22 != 'E' || v23 != 'w' || v24 != 'i' || v25 != '9' || v26 != 'H' )
    v10 = String2;
  else
    v10 = (CHAR *)&v17;
  lstrcpyA((LPSTR)&String1, v10);
  DialogBoxParamA(hInstance, (LPCSTR)0x79, v5, (DLGPROC)sub_1400012E0, 0i64);
  return 1i64;
```

This program first check if the length of input string is 6, then check if it's `6Ewi9H`. Pretty easy!
