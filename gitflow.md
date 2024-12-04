# Gitflow

## 1. Branchs

### 1.1 `main`
- A branch `main` e para produção.
- Só se mergeia na `main` o que está pronto para prod.

### 1.2 `dev`
- A branch `dev` é onde o desenvolvimento acontece.
- Novas funcionalidades, correções de bugs e outras mudanças são feitas aqui.

### 1.3 `Homolog`
- A branch `homolog` é onde é feita a validaçao do desenvolvimento.
- correções de bugs e outras mudanças são feitas aqui.

## 2. branchs Secundárias

### 2.1 Feature (`feature/feature-1`)
- A branch de feature é criada a partir da `develop` para implementar novas funcionalidades.
- Depois de pronta, ela é mesclada de volta em `develop`.

### 2.2 Release (`release/1.0`)
- A branch de release é criada a partir da `develop` quando o código está pronto para o teste final e lançamento.
- Depois de pronta, ela é mesclada em `main` e `develop`.

### 2.3 Hotfix (`hotfix/hotfix-1`)
- A branch de hotfix é criada a partir de `main` para resolver problemas críticos na produção.
- Depois de corrigido, ela é mesclada em `main` e `develop`.

## 3. Resumo do Fluxo

1. **Desenvolvimento de Funcionalidades**: Criar uma branch de feature a partir de `develop` para novas funcionalidades.
2. **Preparação para Lançamento**: Quando o código está pronto, cria-se uma branch de release.
3. **Deploy em Produção**: A branch de release é mesclada em `main` quando o código está pronto para produção.
4. **Correções Rápidas**: Se surgir um bug crítico, uma branch de hotfix é criada para corrigir rapidamente.


