var s, i: integer;
    a: array[1..10] of integer;
begin
  s:=0;
  for i:= 1 to 10 a[i]:=random(100);
  for i:= 1 to 10 write (a[i], ' ');
  for i:= 1 to 10 do s:=s+a[i];
  writeln ('s=', s)
end.
  
