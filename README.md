```pascal
program WhoAmI;

type
  TDeveloper = record
    name     : string;
    school   : string;
    focus    : array of string;
    languages: array of string;
    website  : string;
  end;

procedure describe(dev: TDeveloper);
var i: integer;
begin
  writeln('Identifying target...');
  writeln('    Name      > ', dev.name);
  writeln('    School    > ', dev.school);
  writeln('    Focus     > ');
  for i := 0 to High(dev.focus) do
    writeln('                - ', dev.focus[i]);
    writeln('    Stack     > ', String.Join(', ', dev.languages));
    writeln('    Web       > ', dev.website);
    writeln('Done. No vulnerabilities found... yet.');
end;

var rapido: TDeveloper;
begin
  rapido.name      := '4D4J aka Rapido';
  rapido.school    := 'Oteria — Paris';
  rapido.focus     := ['Vulnerability Research', 'Game Internals / Anti-Cheat Bypass', 'Reverse Engineering'];
  rapido.languages := ['C++', 'Python', 'Assembly', 'and more...'];
  rapido.website   := 'https://www.rapido-cyber.dev';
  describe(rapido);
end.
```

```
Identifying target...
    Name      > 4D4J aka Rapido
    School    > Oteria — Paris
    Focus     >
                - Vulnerability Research
                - Game Internals / Anti-Cheat Bypass
                - Reverse Engineering
    Stack     > C++, Python, Assembly, and more...
    Web       > https://www.rapido-cyber.dev
Done. No vulnerabilities found... yet.
```

---

>  **CVE-2026-18220** — OOB Write in GNU Binutils (`objdump`) &nbsp;|&nbsp; **CVE-2026-38194** — Kernel IOCTL vuln in Teledyne Sapera CORMEM.SYS

---

##  Stats

<p align="center"> 
  <img src="https://github-stats-extended.vercel.app/api?username=4D4J&show_icons=true&theme=radical&hide_border=true&bg_color=0d1117&title_color=ff6e6e&icon_color=ff6e6e&text_color=c9d1d9" height="165"/> &nbsp;&nbsp;     <img src="https://github-stats-extended.vercel.app/api/top-langs/?username=4D4J&layout=compact&theme=radical&hide_border=true&bg_color=0d1117&title_color=ff6e6e&text_color=c9d1d9" height="165"/> 
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=4D4J&theme=radical&hide_border=true&background=0d1117&ring=ff6e6e&fire=ff6e6e&currStreakLabel=ff6e6e" height="165"/>
</p>

---

##  Links

<p align="center">
  <a href="https://www.rapido-cyber.dev">
    <img src="https://img.shields.io/badge/Portfolio-rapido--cyber.dev-ff6e6e?style=for-the-badge&logo=googlechrome&logoColor=white"/>
  </a>
</p>

---

<p align="center"><sub>Rapido (=</sub></p>
