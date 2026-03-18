# 🚀 Wemuv (Protótipo) 
**Marketplace hiperlocal com foco em segurança nas transações e entregas.**

> ⚠️ **Aviso:** Este é um repositório de apresentação (Showcase). O código-fonte oficial e a lógica de negócios estão armazenados em um repositório privado para proteção de Propriedade Intelectual.

## 🔗 Acesse o Protótipo
O MVP está em fase de testes e acessível via web. 
**[Clique aqui para acessar o protótipo na Vercel] (https://wemuv.vercel.app)**

## 💡 O Problema e a Solução
A Wemuv centraliza venda, pagamento e entrega para resolver a falta de confiança em transações locais. O pagamento do comprador fica retido na plataforma e só é liberado para o vendedor após a confirmação rigorosa da entrega, eliminando golpes de ambas as partes.

## ⚙️ Principais Funcionalidades
* **Retenção de Pagamento (Escrow):** O dinheiro só é liberado mediante sucesso da transação.
* **Verificação em Duas Etapas na Entrega:** * O entregador tira uma foto obrigatória do item na coleta (validação de estado).
    * O comprador fornece um código único (PIN/QR Code) gerado no app para liberar o item na entrega.
* **Sistema de Disputas:** Abertura de mediação em até 24h com envio de fotos/vídeos em caso de problemas.

## 🛠️ Arquitetura e Stack Tecnológica
Embora o código seja privado, a infraestrutura do projeto foi desenhada para ser escalável e de rápida resposta:
* **Frontend:** HTML5, CSS3, JavaScript (Vanilla/Framework).
* **Backend & Autenticação:** Firebase (Gerenciamento de usuários e banco de dados em tempo real).
* **Deploy & Hospedagem:** Vercel (CI/CD configurado para atualizações rápidas do protótipo).
