O projeto de um fórum de segurança, criptografia, redes e entre outros termas relevantes para o hacking ético. A ideia é um lugar aonde os membros do labhack podem postar e qualquer aluno acessar a fim de pesquisar.

## Repositorio
https://github.com/HugoCreate/lab-hack-nexus

## Tecnologias
* radix-ui
* supabase
* react
	* react-day-picker
	* react-dom
	* react-hook-form
	* react-resizable-panels
	* react-router-dom
	* recharts
* sonner
* tailwind-merge
* tailwindcss-animate
* vaul
* zod

## Dependências
* eslint js
* tailwindcss
* types
	* node
	* react
	* react-dom
* vite.js
* autoprefixer
* postcss
* typescript
* vite

## Estrutura

Os arquivos do projeto estão organizados da seguinte maneira

```
/
├─node_modules/ 		        # pacotes
├─public/				# arquivos estáticos
├─src/					# diretório principal do projeto
│	├── components			# Componentes reutilizáveis da interface (botões, inputs, cards, etc.) 	
│	├── contexts			# Contextos React para gerenciamento de estado global (ex: autenticação, tema)
│	├── hooks			# Hooks personalizados do React — atualmente contém `useSupabase`, que encapsula o cliente do Supabase para facilitar sua reutilização em componentes.
│	├── integrations		# Integrações externas — contém configuração do Supabase (`supabase.ts`) usada em toda a aplicação.
│	├── lib				# Funções utilitárias, helpers e lógica compartilhada
│	├── pages			# Páginas da aplicação (cada rota corresponde a um arquivo/pasta)
|
|
├─supabase/				# diretório do banco de dados
├─.gitignore				
├─bun.lockb				# Arquivo de lock do Bun (gerencia dependências)
├─components.json			# Lista/registro de componentes (provavelmente para autoimportações ou tooling)
├─eslint.config.js			# Configuração do ESLint (análise de código estático)
├─index.html				# HTML principal para injeção do Vite
├─package.json				# Dependências e scripts do projeto
├─package.json				# Dependências e scripts do projeto
├─postcss.config.js			# Configurações do PostCSS (processamento de CSS)
├─README.md				# Documentação principal do projeto
├─tailwind.config.ts			# Configuração do Tailwind CSS
├─tsconfig.app.json			# Orquestração de contêineres com Docker Compose
├─tsconfig.json				# Dependências e scripts do projeto
├─tsconfig.node.json			# Configurações do TypeScript							
├─vite.config.ts
```
