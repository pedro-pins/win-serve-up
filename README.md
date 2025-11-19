# Arquivos para seguir com a instalação no windows server no baremetal. 

- Tenha certeza que está instalando uma **ISO** direta e oficial da microsoft. 
> Porque essa instrução logo no inicio? **R:** Para evitar retrabalho e um software no baremetal mais seguro possivel. 

##  Passo após final das ferramentas já provisionadas e o baremetal "ok"

- **Importante** Realize um backup antes de efetuar qualquer instalação no baremetal. Principalmente na questão de Rede, Muitas vLans e outros por menores podem ser cruciais
na hora de finalizar o arquivo de configuração ou até mesmo a conexão importante para conexão com seu novo servidor. 

### Salvando o disco

- No baremetal a importancia de indicar e configurar como os discos estão evita de algum erro operacional ou desastre. Então por principio:

```bash
Coloque aqui suas novas configurações
```

> pode ser configuração de RAID ou até mesmo se se servidor está escrevendo em bloco ou sistemas de arquivos é importante para criação segura pós provisionamento.   


## Configurações inicias

- Ativar o RDP com o check name 
- Verificar se o Administrador ou qualquer outro usuário tenha a senha.
> Só assim será efetivada a conexão via RDP do windows. 


### Erros do Baremetal 

- O que pode acontecer e como você pode solucionar: 
1. Erro de Disco
> Geralmente os famosos erro gpt ou o windows não reconhecer o disco por metodo do boot escolhido, para resolver isso é bastante simples: Basta mudar diretamente na bios as configurações de leitura de disco ou forma como o mesmo é montado. **OBS:** Se estiver em RAID verifique como está feito para não haver erro e você conseguir se localizar na escolha do disco certto. 

2. 
