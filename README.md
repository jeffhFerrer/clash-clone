🚀 Sobre o Projeto
Este é um projeto de estudo avançado focado no desenvolvimento de jogos para web utilizando JavaScript Puro (Vanilla) e a API Canvas do HTML5. O objetivo é recriar as mecânicas principais de um jogo de estratégia em tempo real (RTS), como o Clash Royale, sem o uso de motores externos (como Unity ou Phaser).

🎮 Funcionalidades Implementadas
⚔️ Sistema de Batalha (Core Engine)
Inteligência Artificial de Tropas: Sistema de busca de alvos (towers e tropas inimigas) baseado em distância euclidiana.

Lógica de Navegação: As tropas identificam o rio e utilizam as pontes de forma inteligente para atravessar o mapa.

Gerenciamento de Atributos: Cada unidade possui estatísticas únicas de Vida (HP), Dano, Velocidade e Alcance.

Fases de Jogo: Implementação de Tempo Normal, Morte Súbita (Overtime) e Desempate (Tiebreaker) com destruição progressiva de torres.

🃏 Gestão de Deck e Elixir
Rotação de Cartas: Sistema dinâmico que mantém 4 cartas na mão e uma "próxima carta" em espera, simulando fielmente a fila de deck do jogo original.

Economia de Elixir: Regeneração passiva de recursos para invocação de tropas.

🏠 Metagame e Interface (Menu Inicial)
Dashboard do Jogador: Exibição de Nível, XP, Ouro e Gemas.

Sistema de Recompensas: Cálculo de coroas ganhas e ouro recebido após as batalhas, com atualização persistente nos dados do jogador.

Slots de Baús: Interface preparada para recebimento e abertura de baús de recompensa.

🛠️ Tecnologias Utilizadas
Linguagem: JavaScript (ES6+).

Renderização: HTML5 Canvas (2D Context).

Estilização: CSS3 para o container responsivo.

Assets: Sprites simbólicos (Emojis) e imagens externas para telas de carregamento.

📈 Próximos Passos (Roadmap)
[ ] Implementação de sons e efeitos sonoros (SFX).

[ ] Adição de novas cartas com habilidades especiais (ex: tropas aéreas ou feitiços).

[ ] Sistema de salvamento local (LocalStorage) para persistir o progresso entre sessões.

[ ] Melhoria na IA do oponente para realizar jogadas estratégicas de defesa.

💡 Como Contribuir
Se você gostou do projeto e quer ajudar a evoluí-lo:

Dê uma estrela (Star) ⭐ no repositório.

Faça um Fork e experimente criar novas tropas!

Abra uma Issue para sugerir melhorias ou relatar bugs.
