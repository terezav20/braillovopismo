Tento Python skript slouží k převodu normálního textu na text s prefixy podle několika pravidel. Zde je popis, jak skript funguje:

1. <b>Mapování čísel na písmena</b>:
         Skript má definovaný slovník <b><i>number_to_letter</i></b>, který mapuje číslice na odpovídající písmena. Například číslo <i>1</i> se mapuje na písmeno <i>‘a’</i>, číslo <i>2</i> na <i>‘b’</i> atd.
2. <b>Převod velkých písmen</b>:
         Pokud začíná slovo velkým písmenem, skript ho převede na malé písmeno a přidá před něj prefix <b>klávesy 3</b>. Například slovo <i>“Tereza”</i> se převede na <i>“3tereza”</i>.
3. <b>Převod čísel</b>:
         Pokud skript narazí na číslo, převede ho na odpovídající písmena podle mapování v <b><i>number_to_letter</i></b> a přidá před něj prefix <b>klávesy 1</b>. Například číslo <i>123</i> se převede na <i>“1abc”</i>.

Script byl vytvořen jako pomocník při převodu textu pro práci s Braillovým písmem v grafickém editoru, který využívá prefixy.

Pro práci byly řešeny jen prefixy pro číslo a pro velké písmeno, protože ostatní nebudou využívány. Přehled pravidel můžete najít na: [www.tyflokabinet-cb.cz/braill.htm](https://www.tyflokabinet-cb.cz/braill.htm)
