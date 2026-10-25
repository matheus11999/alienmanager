<div align="center">

<img src="docs/logo.png" width="112" alt="Alien Manager" />

# Alien Manager

**Controle de ventoinhas, modos de energia, overlay de jogo e benchmarks para notebooks Alienware.**
Gratuito, leve e sem bloatware.

[![Download](https://img.shields.io/badge/Baixar-Windows%2010%20%2F%2011-3ddc84?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/matheus11999/alienmanager/releases/latest)

![Versão](https://img.shields.io/github/v/release/matheus11999/alienmanager?label=vers%C3%A3o&color=3ddc84)
![Downloads](https://img.shields.io/github/downloads/matheus11999/alienmanager/total?color=1fd6a0)
![Preço](https://img.shields.io/badge/pre%C3%A7o-gr%C3%A1tis-b6ff6b)

<img src="docs/screenshots/painel.png" alt="Painel do Alien Manager" width="900" />

</div>

## Recursos

- **Painel**: temperaturas de CPU e GPU em destaque, uso, potência, memória, armazenamento e bateria.
- **Modos de operação**: Silencioso, Equilibrado, Desempenho, G‑Mode, Máximo e os perfis do BIOS, num clique.
- **Perfis personalizados**: crie curvas de ventoinha por temperatura, com nome, ícone, cor e limite térmico (TCC) próprios.
- **Atalhos globais**: associe uma tecla a cada modo ou perfil e troque no meio do jogo. Um aviso na tela confirma a troca.
- **Overlay de jogo**: FPS, média da sessão, 1% low, tempo de quadro, temperaturas, uso de CPU/GPU, potência, RAM e bateria. Escolha cada linha, ajuste a transparência e veja o alerta acima de 85 °C.
- **Benchmarks da comunidade**: grave uma sessão de jogo e compare com outros jogadores. Ranking aberto a todos, com busca, filtros por jogo, qualidade, resolução, upscaling e GPU, gráfico por notebook e comparação lado a lado.
- **Resultados confiáveis**: o FPS é recalculado no servidor a partir dos quadros gravados e assinados pelo app, o jogo é identificado pelo executável e resultados fora da curva ficam ocultos até revisão.
- **Contas e níveis**: crie sua conta no próprio app (só usuário e senha) e ganhe XP jogando com o overlay ligado, de Iniciante a Lenda.
- **Iluminação**: brilho do teclado e tempo para apagar na tomada e na bateria; RGB AlienFX em beta.
- **Ventoinhas e sensores**: rotação ao vivo, boost manual, temperaturas de CPU, GPU, placa‑mãe e SSD.
- **Atualizações automáticas**: o app avisa quando há versão nova e atualiza em um clique, mostrando as novidades.
- **Do seu jeito**: cor principal, Mica/Acrílico do Windows 11, iniciar com o Windows, minimizar na bandeja.

## Capturas

<div align="center">
<b>Ranking da comunidade</b><br />
<img src="docs/screenshots/benchmarks.png" width="900" />
</div>

| Gráfico por notebook | Comparação lado a lado |
|:-:|:-:|
| <img src="docs/screenshots/bench-grafico.png" width="440" /> | <img src="docs/screenshots/bench-comparar.png" width="440" /> |
| **Ventoinhas** | **Sensores** |
| <img src="docs/screenshots/ventoinhas.png" width="440" /> | <img src="docs/screenshots/sensores.png" width="440" /> |
| **Perfis** | **Iluminação** |
| <img src="docs/screenshots/perfis.png" width="440" /> | <img src="docs/screenshots/iluminacao.png" width="440" /> |
| **Overlay** | **Configurações** |
| <img src="docs/screenshots/overlay-config.png" width="440" /> | <img src="docs/screenshots/config.png" width="440" /> |

<table>
  <tr>
    <td align="center"><b>Overlay em jogo</b><br /><img src="docs/screenshots/overlay.png" width="260" /></td>
    <td align="center"><b>Aviso de troca de modo</b><br /><img src="docs/screenshots/hud.png" width="340" /><br /><br /><b>Instalador</b><br /><img src="docs/screenshots/instalador.png" width="380" /></td>
  </tr>
</table>

## Instalação

1. Baixe **AlienManager-Setup-x.y.z.exe** na página de [releases](https://github.com/matheus11999/alienmanager/releases/latest).
2. Execute e clique em **Instalar**. Pronto.

> O Windows pode mostrar o aviso do SmartScreen porque o instalador ainda não tem assinatura de código. Clique em **Mais informações → Executar assim mesmo**.

Também há uma versão **portátil** (.zip) na mesma página, que roda sem instalar.

**Requisitos:** Windows 10 ou 11 (64 bits), notebook Alienware ou Dell G com AWCC/BIOS compatível. O app pede permissão de administrador porque conversa direto com o controlador térmico.

## Atalhos padrão

| Atalho | Ação |
|---|---|
| `Ctrl + Shift + O` | Mostrar/ocultar o overlay |
| `Ctrl + Shift + L` | Travar/destravar o overlay |
| `Ctrl + Shift + R` | Reiniciar a média de FPS da sessão |
| `Ctrl + Shift + B` | Iniciar/parar a gravação de um benchmark |
| Definidos por você | Trocar de modo ou perfil (Configurações → Atalhos) |

## Privacidade

O app envia, de forma anônima, a versão, o modelo do notebook e mensagens de erro, para aperfeiçoar o programa e corrigir incompatibilidades com mais modelos. Nenhum dado pessoal é coletado. Dá para desligar no instalador ou em **Configurações → Geral**. A conexão com o servidor é criptografada.

## Próximos passos

O Alien Manager é **gratuito e vai continuar recebendo atualizações e novos recursos**.

## Créditos

- O controle de hardware é baseado no SDK **alienfan** do projeto [alienfx-tools](https://github.com/T-Troll/alienfx-tools) (licença MIT), via interface WMI do AWCC.
- Captura de FPS com [Intel PresentMon](https://github.com/GameTechDev/PresentMon) (licença MIT, incluída em `docs/LICENSE-PresentMon.txt`).
- Desenvolvido com ajuda de IA.

O código‑fonte não é público. Uso gratuito; veja [LICENSE](LICENSE).

---

<sub>Alien Manager é um projeto independente, sem afiliação com a Dell Technologies ou com a marca Alienware. Alienware é marca registrada de seus respectivos donos.</sub>
