# 🚀 Lab - Site Estático na AWS S3 com CloudFront e HTTPS

Este é meu primeiro laboratório prático em Cloud Computing, onde hospedei um site estático utilizando Amazon S3 e distribuí com CloudFront para HTTPS e melhor performance.
O objetivo é demonstrar conhecimentos básicos de armazenamento, hosting e distribuição de conteúdo na nuvem.

---

## 🛠️ Serviços Utilizados
- **Amazon S3** → Para armazenamento dos arquivos do site.
- **AWS CloudFront** → Distribuição do site com HTTPS.
- **AWS Management Console** → Para configuração do bucket e permissões.

---

## ⚙️ Passo a Passo do Deploy
1. Criar um bucket no **Amazon S3**.
2. Fazer upload do arquivo `index.html`.
3. Ativar a opção **Static website hosting** no bucket.
4. Ajustar as permissões de leitura pública.
5. Criar uma distribuição **CloudFront** apontando para o bucket S3.
6. Configurar o **Default Root Object** como `index.html`.
7. Criar uma **Invalidation** no CloudFront (`/*`) para atualizar o cache.

---

## 📸 Demonstração
<img width="1707" height="631" alt="image" src="https://github.com/user-attachments/assets/0a77bd61-a042-475f-a172-21f27bc452bb" />

---

## 🔗 **URL do site hospedado:**  
[👉 Clique aqui para acessar](https://d2iiioq566swwz.cloudfront.net/)

---

## 📚 Aprendizados
- Como criar e configurar um bucket no S3.
- Diferença entre **armazenamento de objetos** e **hospedagem web tradicional**.
- Deploy de site estático sem servidor.
- Distribuição de conteúdo via CloudFront com HTTPS e cache.

---

✍️ **Autor:** Victor Oliveira
