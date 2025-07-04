<style>
.popup-overlay {
  position: fixed;
  top: 0; left: 0;
  width: 100%; height: 100%;
  background-color: rgba(0, 0, 0, 0.6);
  display: none;
  justify-content: center;
  align-items: center;
  z-index: 9999;
  padding: 0 1rem;
}
.popup-box {
  background: #fff;
  border: 4px solid #1b8f5b;
  padding: 2rem 2rem 1rem 2rem;
  width: calc(100% - 4rem); /* ocupa tudo com margem lateral */
  max-width: 1000px;        /* ou o limite do tema */
  border-radius: 0;
  position: relative;
  font-family: sans-serif;
  max-height: 80vh;
  overflow-y: auto;
  box-sizing: border-box;
}
.popup-close {
  position: absolute;
  top: 10px; right: 15px;
  font-size: 1.5rem;
  cursor: pointer;
  color: #1b8f5b;
}
.popup-title {
  text-align: center;
  font-weight: bold;
  font-size: 1.5rem;
  color: #1b8f5b;
  margin-bottom: 1.5rem;
}
.popup-box p {
  margin-bottom: 1rem;
  line-height: 1.5;
  color: #000;
}
.popup-box a {
  color: #1b8f5b !important;
  font-weight: bold;
  text-decoration: none;
}
.popup-box a:hover {
  text-decoration: underline;
  color: #145635 !important;
}
.popup-button-wrapper {
  text-align: center;
  margin: 2rem 0;
}
.popup-button {
  padding: 10px 20px;
  background-color: #1b8f5b;
  color: #fff;
  border: none;
  border-radius: 0;
  font-size: 1rem;
  cursor: pointer;
}
</style>

<div class="popup-button-wrapper">
  <button class="popup-button" onclick="document.querySelector('.popup-overlay').style.display='flex'">Entrevistados</button>
</div>

<div class="popup-overlay">
  <div class="popup-box">
    <span class="popup-close" onclick="document.querySelector('.popup-overlay').style.display='none'">&times;</span>
    <div class="popup-title">Entrevistados</div>

    <p><a href="https://www.escavador.com/sobre/4164980/camilo-de-oliveira-aggio" target="_blank" rel="noopener noreferrer">Camilo de Oliveira Aggio</a>: Professor e pesquisador da Universidade Federal de Minas Gerais (UFMG) a respeito da presença de Jair Messias Bolsonaro nas redes e doutor em Comunicação e Cultura Contemporânea</p>

    <p><a href="https://www.escavador.com/sobre/6711834/demian-bezerra-de-melo" target="_blank" rel="noopener noreferrer">Demian Bezerra de Melo</a>: Professor Adjunto de História Contemporânea do curso de Políticas Públicas da Universidade Federal Fluminense (UFF), doutor em história e pesquisador a respeito do Bolsonarismo e o Fascismo. Participante voluntário da Comissão Nacional da Verdade</p>

    <p><a href="https://www.escavador.com/sobre/4029556/emilio-peluso-neder-meyer" target="_blank" rel="noopener noreferrer">Emílio Peluso Neder Meyer</a>: Doutor em direito, pesquisador a respeito do bolsonarismo e Professor de Teoria da Constituição, Teoria do Estado e Direito Constitucional no Curso de Graduação e no Programa de Pós-Graduação em Direito da Faculdade de Direito da UFMG</p>

    <p><a href="https://www.escavador.com/sobre/6493049/jose-de-assis-santiago-neto" target="_blank" rel="noopener noreferrer">José de Assis Santiago Neto</a>: Doutor em Direito Processual e professor de direito penal e processual da PUC Minas</p>

    <p><a href="https://www.escavador.com/sobre/535550/malco-braga-camargos" target="_blank" rel="noopener noreferrer">Malco Braga Camargos</a>: Doutor em Ciência Política, professor da PUC Minas, diretor do Instituto Ver Pesquisa e Estratégia</p>

    <p><a href="https://www.escavador.com/sobre/7085116/nara-lya-simoes-caetano-cabral" target="_blank" rel="noopener noreferrer">Nara Lya Cabral Scabin</a>: Doutora em Ciências da Comunicação, professora de jornalismo e pesquisadora da linha de Poder e Processos Sociotécnicos do PPGCOM da PUC Minas</p>

    <p><a href="https://www.escavador.com/sobre/6204704/paulo-henrique-paschoeto-cassimiro" target="_blank" rel="noopener noreferrer">Paulo Henrique Paschoeto Cassimiro</a>: Professor do departamento de ciência política da Uerj, doutor em ciência política e pesquisador a respeito do populismo reacionário</p>

    <p><a href="http://lattes.cnpq.br/0242663293732863" target="_blank" rel="noopener noreferrer">Robson Sávio Reis Souza</a>: Coordenador da Comissão da Verdade em Minas Gerais, sociólogo, doutor em ciências sociais, professor da PUC Minas e pesquisador a respeito do bolsonarismo e autoritarismo</p>

    <p><a href="https://www.escavador.com/sobre/4477844/wallison-alves-brandao" target="_blank" rel="noopener noreferrer">Wallison Alves Brandão</a>: Doutorando em Ciências Sociais, professor de Filosofia e Sociologia e pesquisador a respeito dos Golpes de Estado na América Latina</p>
  </div>
</div>
