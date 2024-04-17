# WP-Portugal i18n Build Files

Um pacote do WordPress é um ficheiro ZIP que consiste no WordPress na sua totalidade, juntamente com ficheiros de tradução do *core*, os temas por omissão, o Akismet, e quaisquer personalizações que possam existir.

Neste repositório são mantidos os ficheiros personalizados incluídos na distribuição do WordPress traduzida para português (Portugal).

### Estrutura de ficheiros e pastas deste repositório

- `/en_US` - Ficheiros originais em inglês, actualizados automaticamente pela [acção](https://github.com/wp-portugal/wp-portugal-i18n-build-files/actions/workflows/update-build-files.yml)
- `/pt_PT` - Versões traduzidas para português, actualizadas manualmente.

### Sobre a criação automática de actualizações no WordPress.org

- https://pt.wordpress.org/team/2024/04/17/lancamento-automatizado-de-novas-versoes/
- https://make.wordpress.org/polyglots/handbook/for-editors/packaging-localized-wordpress/automated-release-packages/

### Ficheiros originais em *Trunk*

- https://github.com/WordPress/wordpress-develop/blob/trunk/src/readme.html
- https://github.com/WordPress/wordpress-develop/blob/trunk/wp-config-sample.php

### Versões traduzidas `[pt_PT]`

- https://i18n.svn.wordpress.org/pt_PT/branches/

### Os ficheiros deste repositório estão em Pré-AO90[^1], como é criado o pacote AO90[^2]?

Os ficheiros deste repositório são referentes ao pacote traduzido para a instalação manual do WordPress, disponibilizado em [WordPress.org/download](https://pt.wordpress.org/download/).

A [Comunidade Portuguesa de WordPress](https://wp-portugal.com/comunidade-portuguesa-wordpress/) fornece a tradução em ambas as variantes, **Pré-AO90** e **AO90**.

A tradução do *core* do WordPress é feita em [Pré-AO90](https://translate.wordpress.org/locale/pt/default/wp/dev/), e convertida *automaticamente* para [AO90](https://translate.wordpress.org/locale/pt/ao90/wp/dev/).

Depois da instalação concluída, pode escolher a variante desejada para o seu site em **Opções > Geral > Idioma do site**, ou para o seu utilizador em **Utilizadores > Perfil > Idioma**.

Para mais informações sobre a tradução portuguesa do WordPress, consulte a documentação em [wp-portugal.com/traducao](https://wp-portugal.com/traducao/).

[^1]: Acordo Ortográfico de 1945.
[^2]: Acordo Ortográfico de 1990.
