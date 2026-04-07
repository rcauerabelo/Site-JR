<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Jr Transcrições | Traduções Juramentadas</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;700&family=Inter:wght@300;400;500&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Inter', sans-serif;
      background: #f8fafc;
      color: #1f2933;
    }

    header {
      background: linear-gradient(135deg, #0f172a, #1e293b);
      color: #ffffff;
      padding: 80px 20px;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-family: 'Playfair Display', serif;
      font-size: 3rem;
      letter-spacing: 1px;
    }

    header p {
      margin-top: 15px;
      font-size: 1.2rem;
      font-weight: 300;
      max-width: 700px;
      margin-left: auto;
      margin-right: auto;
    }

    section {
      max-width: 1000px;
      margin: 70px auto;
      padding: 0 25px;
    }

    section h2 {
      font-family: 'Playfair Display', serif;
      font-size: 2.2rem;
      margin-bottom: 25px;
      text-align: center;
    }

    section p {
      font-size: 1.1rem;
      line-height: 1.8;
      text-align: center;
      max-width: 800px;
      margin: 0 auto;
    }

    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 25px;
      margin-top: 50px;
    }

    .card {
      background: #ffffff;
      border-radius: 16px;
      padding: 35px 30px;
      box-shadow: 0 10px 25px rgba(0,0,0,0.06);
      transition: transform 0.3s ease;
    }

    .card:hover {
      transform: translateY(-6px);
    }

    .card h3 {
      font-family: 'Playfair Display', serif;
      margin-top: 0;
      margin-bottom: 15px;
      font-size: 1.4rem;
    }

    .card p {
      font-size: 1rem;
      line-height: 1.6;
      text-align: left;
    }

    .buttons {
      margin-top: 60px;
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
    }

    .buttons a {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      gap: 10px;
      text-decoration: none;
      padding: 14px 28px;
      font-size: 0.95rem;
      border-radius: 999px;
      font-weight: 500;
      letter-spacing: 0.3px;
      box-shadow: 0 6px 18px rgba(0,0,0,0.12);
      transition: all 0.25s ease;
    }

    .buttons a:hover {
      transform: translateY(-2px);
      box-shadow: 0 10px 28px rgba(0,0,0,0.18);
    }

    .btn {
      text-decoration: none;
      padding: 16px 34px;
      font-size: 1rem;
      border-radius: 10px;
      color: #ffffff;
      font-weight: 500;
      transition: all 0.3s ease;
    }

    .btn-whatsapp {
      background: #16a34a;
    }

    .btn-whatsapp:hover {
      background: #15803d;
    }

    .btn-email {
      background: #1d4ed8;
    }

    .btn-email:hover {
      background: #1e40af;
    }

    footer {
      background: #0f172a;
      color: #cbd5e1;
      text-align: center;
      padding: 35px 20px;
      font-size: 0.9rem;
    }
  .faq-item {
  background: #ffffff;
  border-radius: 12px;
  padding: 18px 22px;
  margin-bottom: 15px;
  cursor: pointer;
  transition: box-shadow 0.3s ease;
}

.faq-item:hover {
  box-shadow: 0 8px 20px rgba(0,0,0,0.08);
}

.faq-header {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.faq-arrow {
  font-size: 18px;
  transition: transform 0.3s ease;
}

.faq-item.active .faq-arrow {
  transform: rotate(90deg);
}

.faq-content {
  max-height: 0;
  overflow: hidden;
  transition: max-height 0.4s ease;
}

.faq-item.active .faq-content {
  max-height: 300px;
  margin-top: 12px;
}
</style>

  <script>
    function toggleFaq(id) {
      const faqs = document.querySelectorAll('[id^="faq"]');
      faqs.forEach(faq => {
        if (faq.id === id) {
          faq.style.display = faq.style.display === 'block' ? 'none' : 'block';
        } else {
          faq.style.display = 'none';
        }
      });
    }
  </script>
</head>
<body>

  <header>
    <h1>Jr Transcrições</h1>
    <p>
      Escritório especializado em traduções juramentadas e traduções oficiais de documentos,
      com rigor técnico, sigilo absoluto e validade legal.
    </p>
  </header>

  <section>
    <h2>Excelência em Tradução Juramentada</h2>
    <p>
      Atuamos com traduções juramentadas e não juramentadas para fins legais, acadêmicos e comerciais.
      Nossos serviços seguem os padrões exigidos por órgãos oficiais, cartórios, universidades e consulados.
    </p>

    <div class="cards">
      <div class="card">
        <h3>Idiomas Atendidos</h3>
        <p>
          Traduções juramentadas realizadas por tradutores públicos oficiais nos idiomas:<br><br>
          • Inglês<br>
          • Espanhol<br>
          • Francês<br>
          • Italiano
        </p>
      </div>
      

      <div class="card">
        <h3>Documentos Oficiais</h3>
        <p>
          Certidões, contratos, diplomas, históricos escolares,
          documentos pessoais e empresariais.
        </p>
      </div>

      <div class="card">
        <h3>Sigilo e Confiabilidade</h3>
        <p>
          Tratamos todos os documentos com total confidencialidade,
          garantindo segurança e integridade das informações.
        </p>
      </div>
    </div>

    <div class="buttons" style="margin-top:80px; margin-bottom:40px;">
      <a href="https://wa.me/5511986844016" target="_blank" style="background:#16a34a; color:#ffffff;">💬 Solicitar Orçamento via WhatsApp</a>
      <a href="mailto:jrtoninha@uol.com.br" style="background:#1d4ed8; color:#ffffff;">✉️ Solicitar Orçamento por E-mail</a>
    </div>

    <h2>Dúvidas Frequentes</h2>

    <div class="cards">
      <div class="card">
        <h3 style="cursor:pointer;" onclick="toggleFaq('faq1')">A tradução juramentada é aceita por consulados, imigração e cartórios? </h3>
        <p id="faq1" style="display:none;">
          Sim. A tradução juramentada possui fé pública e é aceita por consulados, embaixadas,
          órgãos de imigração, cartórios, universidades e instituições oficiais, conforme as
          exigências de cada órgão.
        </p>
      </div>

      <div class="card">
        <h3 style="cursor:pointer;" onclick="toggleFaq('faq2')">A tradução juramentada digital tem a mesma validade? </h3>
        <p id="faq2" style="display:none;">
          Sim. A tradução juramentada digital, quando assinada digitalmente pelo tradutor público
          juramentado, possui a mesma validade legal da versão física e é amplamente aceita
          pelos órgãos competentes.
        </p>
      </div>

      <div class="card">
        <h3 style="cursor:pointer;" onclick="toggleFaq('faq3')">Preciso enviar o documento original para tradução? </h3>
        <p id="faq3" style="display:none;">
          Na maioria dos casos, não. A tradução juramentada pode ser realizada a partir de uma cópia
          digital legível do documento original, enviada por e-mail ou WhatsApp.
        </p>
      </div>

      <div class="card">
        <h3 style="cursor:pointer;" onclick="toggleFaq('faq4')">Qual o prazo para realizar uma tradução juramentada? </h3>
        <p id="faq4" style="display:none;">
          O prazo varia conforme o tipo, volume e idioma do documento. Após a análise,
          informamos o prazo estimado juntamente com o orçamento.
        </p>
      </div>

      <div class="card">
        <h3 style="cursor:pointer;" onclick="toggleFaq('faq5')">A tradução juramentada tem prazo de validade? </h3>
        <p id="faq5" style="display:none;">
          Não. A tradução juramentada não possui prazo de validade. Contudo, alguns órgãos podem
          exigir que o documento original esteja atualizado.
        </p>
      </div>

      <div class="card">
        <h3 style="cursor:pointer;" onclick="toggleFaq('faq6')">Como é feito o orçamento da tradução? </h3>
        <p id="faq6" style="display:none;">
          O orçamento é calculado com base no tipo de documento, idioma e volume de texto.
          Basta enviar o arquivo por WhatsApp ou e-mail para análise sem compromisso.
        </p>
      </div>
    </div>

    
          </section>

  <footer>
    <p>© Desde 2011 Jr Transcrições — Traduções Juramentadas e Oficiais</p>
    <p>
      CNPJ: 4.033.141/0001-15<br>
      Rua Vinte e Quatro de Maio, 35, Andar 10, Sala 1014, Bairro República,<br>
      São Paulo - SP, CEP 01041-911
    </p>
  </footer>

</body>
</html>
