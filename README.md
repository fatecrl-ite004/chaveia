# CHAVEIA

![GitHub repo size](https://img.shields.io/github/repo-size/Giovanna-annavoiG/chaveia?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/Giovanna-annavoiG/chaveia?style=for-the-badge)
![GitHub open issues](https://img.shields.io/github/issues/Giovanna-annavoiG/chaveia?style=for-the-badge)
![GitHub open pull requests](https://img.shields.io/github/issues-pr/Giovanna-annavoiG/chaveia?style=for-the-badge)


> CHAVEIA é uma plataforma web de fricção zero para organização e chaveamento de esportes de areia na orla da Baixada Santista. O sistema automatiza torneios e conecta atletas avulsos a partidas com vagas abertas sem necessidade de cadastros extensos.

## Ajustes e melhorias

O projeto está em desenvolvimento ativo e as próximas etapas compreendem as seguintes tarefas:

- [x] Estruturação da documentação e MVP
- [x] Repositório, padrões de commits e branches e ambiente de desenvolvimento (React + Vite + Supabase)
- [ ] Criação das telas da interface em React (PWA Mobile-First)
- [ ] Modelagem e implementação do banco de dados PostgreSQL no Supabase
- [ ] Desenvolvimento do algoritmo de chaveamento reativo
- [ ] Integração com o mural público de desfalques e API oceanográfica

## Pré-requisitos

Antes de começar, certifique-se de preencher os seguintes requisitos:

1. Possuir o Node.js (versão LTS), o npm e o Git instalados na máquina de desenvolvimento, e uma conta gratuita no Supabase para criar o seu próprio projeto.
2. Compatível com sistemas operacionais Windows, Linux e macOS para desenvolvimento, e navegadores web móveis (Android/iOS) para execução.
3. Leitura prévia da documentação técnica.

## Instalando CHAVEIA

Para clonar e configurar o repositório localmente, siga os passos abaixo:

Linux e macOS:
```bash
git clone https://github.com/Giovanna-annavoiG/chaveia.git
cd chaveia
npm install
cp .env.example 
npm run dev
```
Windows:
```powershell
git clone https://github.com/Giovanna-annavoiG/chaveia.git
cd chaveia
npm install
Copy-Item .env.example
npm run dev
```

Antes do `npm run dev`, abra o arquivo `.env` e preencha a URL e a chave pública do seu projeto Supabase. Esse arquivo contém credenciais e nunca deve ser enviado ao GitHub (já está no `.gitignore`).

---
## Contribuindo para CHAVEIA

Para contribuir com Chaveia, siga estas etapas:

1. Bifurque este repositório.
2. Crie um branch: `git checkout -b <nome_branch>`.
3. Faça suas alterações e confirme-as: `git commit -m '<mensagem_commit>'`
4. Envie para o branch original: `git push origin <nome_branch>`
5. Crie a solicitação de pull.

Os padrões de nomes de branches e de mensagens de commit estão em [CONTRIBUTING.md](CONTRIBUTING.md).

Como alternativa, consulte a documentação do GitHub em [como criar uma solicitação pull](https://docs.github.com/pt/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request).
