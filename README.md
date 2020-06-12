# hodnoceni-2020-mtg

Hodnocení pro letní tábor 2020. Záloha kartiček, pravidel hry
a TeXovského skriptu k vysázení kartiček k tisku.

## Jak aktualizovat PDF k tisku

```
xelatex layout.tex
```

Vysází šest karet na stránku formátu A4. Každá karta z adresáře
`cards` bude v PDF v počtu kopií definovaném v `layout.tex`. Karty
k vysázení nahrávají soubory věnované dané cenové skupině
`layout_XY.tex`.
