Použití AI v projektu

Při tvorbě stránky jsem AI použil na nějaké věci.

Responzivita

S AI jsem řešil hlavně část, která zajišťuje, aby se stránka správně zobrazovala na mobilu. Nepamatoval jsem si, jak se přesně dělá responzivní verze, takže jsem si nechal poradit s touto částí CSS:

```css
@media (max-width: 640px) {
    .menu-btn { display: block; }

    nav {
        position: absolute;
        top: 72px;
        left: 0;
        right: 0;
        background: #eef1f4;
        border-bottom: 2px solid #22262b;
        display: none;
    }

    nav.open { display: block; }

    nav ul {
        flex-direction: column;
        gap: 0;
        padding: 8px 24px 16px;
    }

    nav a { display: block; padding: 12px 0; }

    .hero h1 { font-size: 34px; }
    .projects a { grid-template-columns: 1fr; gap: 6px; }
}
```

Díky tomu se na menších obrazovkách zobrazí tlačítko menu, navigace se skryje a otevře se až po kliknutí, odkazy jsou pod sebou a nadpis i seznam projektů se přizpůsobí šířce displeje.

Vzhled stránky

Kromě toho jsem se AI občas zeptal na grafické věci, například na barvy, rozestupy nebo rozložení prvků, aby stránka vypadala aspoň trochu dobře.
