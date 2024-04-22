Tento Python skript slouží k převodu normálního textu na text s prefixy podle několika pravidel. Zde je popis, jak skript funguje:

1. Mapování čísel na písmena:
         Skript má definovaný slovník number_to_letter, který mapuje číslice na odpovídající písmena. Například číslo 1 se mapuje na písmeno ‘a’, číslo 2 na ‘b’ atd.
2. Převod velkých písmen:
         Pokud začíná slovo velkým písmenem, skript ho převede na malé písmeno a přidá před něj prefix klávesy 3. Například slovo “Tereza” se převede na “3tereza”.
3. Převod čísel:
         Pokud skript narazí na číslo, převede ho na odpovídající písmena podle mapování v number_to_letter a přidá před něj prefix klávesy 1. Například číslo 123 se převede na “1abc”.

Script byl vytvořen jako pomocník při převodu textu pro práci s Braillovým písmem v grafickém editoru, který využívá prefixy.

Pro práci byly řešeny jen prefixy pro číslo a pro velké písmeno, protože ostatní nebudou využívány. Přehled pravidel můžete najít na: https://www.tyflokabinet-cb.cz/braill.htm
