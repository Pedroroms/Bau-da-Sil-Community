# Segurança e privacidade

O Baú da Sil Community usa um motor Node.js local. Informações como token, licença, sessão vinculada do WhatsApp e diagnósticos podem ficar armazenadas em `.dados-locais` no computador do participante.

**Nunca publique nem envie** `.dados-locais`, `.segredos`, `ADMIN-EXCLUSIVO`, tokens, QR Codes, senhas ou licenças completas. O pacote público deve conter apenas a **chave pública** de verificação, nunca a chave privada do administrador.

A licença offline é assinada digitalmente e possui vencimento. **Não impede cópias entre computadores nem permite revogação remota imediata.** A comunicação entre a extensão e o motor ocorre via `127.0.0.1:18443`, autenticada por token local.

A ferramenta usa **Baileys**, integração não oficial com WhatsApp; o serviço pode mudar ou restringir contas. Use apenas em grupos onde exista permissão e com contatos que solicitaram as ofertas. Não use para disparos em massa ou mensagens não solicitadas.

Ferramenta independente e sem vínculo oficial com o catálogo da Ana, Shopee, WhatsApp ou Meta.

☀️ Criado pela Comandante Sol
