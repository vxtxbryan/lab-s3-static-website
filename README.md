# 🚀 Lab - Site Estático na AWS S3 com CloudFront, HTTPS e Deploy Automático

Este é meu primeiro laboratório prático em Cloud Computing, onde hospedei um site estático utilizando Amazon S3 e distribuí com CloudFront para HTTPS e melhor performance.
O objetivo é demonstrar conhecimentos básicos de armazenamento, hosting e distribuição de conteúdo na nuvem, agora com deploy automatizado via GitHub Actions.

---

## 🛠️ Serviços Utilizados
- **Amazon S3** → Para armazenamento dos arquivos do site.
- **AWS CloudFront** → Distribuição do site com HTTPS.
- **AWS Management Console** → Para configuração do bucket e permissões.
- **GitHub Actions** → Automação do deploy do site.

---

## ⚙️ Passo a Passo do Deploy
1. Criar um bucket no **Amazon S3**.
2. Fazer upload do arquivo `index.html`.
3. Ativar a opção **Static website hosting** no bucket.
4. Ajustar as permissões de leitura pública.
5. Criar uma distribuição **CloudFront** apontando para o bucket S3.
6. Configurar o **Default Root Object** como `index.html`.
7. Criar uma **Invalidation** no CloudFront (`/*`) para atualizar o cache.
8. **Deploy Automático**: agora, qualquer alteração na branch `main` do GitHub aciona o workflow do GitHub Actions, que:
   - Sincroniza os arquivos para o bucket S3.
   - Invalida o cache do CloudFront.
   - Garante que o site esteja sempre atualizado sem uploads manuais.

---

## 📸 Demonstração
<img width="1915" height="502" alt="image" src="https://github.com/user-attachments/assets/1b94b4db-9122-4e4f-869a-c50f17d61d86" />

---

## 🔗 **URL do site hospedado:**  
[👉 Clique aqui para acessar](https://d2iiioq566swwz.cloudfront.net/)

---

## 📚 Aprendizados
- Como criar e configurar um bucket no S3.
- Diferença entre **armazenamento de objetos** e **hospedagem web tradicional**.
- Deploy de site estático sem servidor.
- Distribuição de conteúdo via CloudFront com HTTPS e cache.
- **Automação de deploy com GitHub Actions**, reduzindo erros e tempo gasto.
- CI/CD básico, focado em deploy de site estático.

---

✍️ **Autor:** Victor Oliveira
