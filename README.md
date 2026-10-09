# MobileAtlas

Portal estático de estudos Android/iOS, em português. HTML, CSS e JS no index.html, sem build ou backend.

## Trilhas
- Iniciante: 24 semanas, 8–10 h/semana; projeto Bloom de hábitos.
- Intermediário: 16 semanas, 10–12 h/semana; projeto financeiro Luma.
- Avançado: 12 semanas, 10–12 h/semana; projeto Luma Pro.

Cada semana tem tópicos, exercício, entregável, critérios, checklist de evidências e anotações. Os prazos são sugestões, não certificação de senioridade.

## Progresso
localStorage usa mobile-atlas-v2, separado por plataforma e nível. Não há sincronização entre dispositivos. Exportar/importar JSON permite backup. O estado v1, quando encontrado no mesmo domínio, fica preservado no backup e não é mapeado automaticamente porque o currículo mudou. Mudar de origem, domínio ou navegador cria outro armazenamento. Dados podem ser apagados pelo navegador. Se localStorage não estiver disponível, use exportação.

## Referências e projeto
As telas são mockups em HTML/CSS, com dados fictícios, e a seleção abre especificações. Não são aplicativos nativos funcionais. Use fixtures/API mock para o projeto financeiro; não há integração bancária. Para iOS, desenvolvimento requer Mac com Xcode. Distribuição TestFlight/lojas é opcional e pode exigir contas e taxas. Fontes Google são opcionais: há fallback do sistema.

## Validação manual
- Selecionar as seis combinações plataforma/nível.
- Abrir fases, pesquisar assuntos e filtrar semanas.
- Marcar as três evidências e concluir uma semana.
- Recarregar: dados preservados; mudar de trilha: progresso independente.
- Registrar notas, mover sliders, exportar e importar backup.
- Clicar nas três telas e conferir especificações.
- Testar teclado, fonte ampliada e viewport mobile.

## Fontes
- Android Basics with Compose: https://developer.android.com/courses/android-basics-compose/course
- Offline-first: https://developer.android.com/topic/architecture/data-layer/offline-first
- Swift Tour: https://docs.swift.org/latest/documentation/the-swift-programming-language/guidedtour/
- Swift Concurrency: https://docs.swift.org/latest/documentation/the-swift-programming-language/concurrency/
- Instruments: https://developer.apple.com/tutorials/instruments
