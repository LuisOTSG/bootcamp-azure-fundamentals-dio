## **Identificando os Componentes de Arquitetura do Azure**

### **Descrição**

No Microsoft Azure, a arquitetura é composta por diversos componentes que colaboram para construir soluções escaláveis e resilientes. Seu desafio é criar um código que associe cada componente de arquitetura do Azure com sua descrição correspondente. O objetivo é identificar e mapear corretamente os componentes para suas funções principais.

### **Entrada**

A entrada para o desafio consiste em um componente de arquitetura do Azure para o qual você deve retornar a descrição correspondente. Os seguintes componentes são válidos para este desafio:

- `"Regiões do Azure"`
- `"Zonas de Disponibilidade"`
- `"Datacenters"`
- `"Assinaturas"`
- `"Grupos de Gerenciamento"`

### **Saída**

A saída esperada é a descrição associada ao componente fornecido como entrada. Seguem as saídas possíveis, **listadas aleatoriamente**, para que você possa analisar e associar corretamente:

- `"Unidades de faturamento que agrupam recursos e serviços do Azure"`
- `"Instalações físicas que abrigam servidores e outros recursos"`
- `"Estruturas hierárquicas que gerenciam múltiplas assinaturas"`
- `"Garante alta disponibilidade ao isolar falhas"`
- `"Localizações geográficas onde os serviços são disponibilizados"`

```python
# Recebe a Entrada do usuário e armazena na variável "entrada"
entrada = input()

# Função responsável por receber um serviço de armazenamento e retornar sua respectiva descrição.
def identificar_componente(componente):
    if componente == "Datacenters":
        return "Instalações físicas que abrigam servidores e outros recursos"
    elif componente == "Regiões do Azure":
        return "Localizações geográficas onde os serviços são disponibilizados"
    elif componente == "Assinaturas":
        return "Unidades de faturamento que agrupam recursos e serviços do Azure"
    elif componente == "Zonas de Disponibilidade":
        return "Garante alta disponibilidade ao isolar falhas"
    elif componente == "Grupos de Gerenciamento":
        return "Estruturas hierárquicas que gerenciam múltiplas assinaturas"
        
print(identificar_componente(entrada))
```

## **Explorando os Serviços de Armazenamento do Azure**

### **Descrição**

O armazenamento na Microsoft Azure oferece uma variedade de serviços para atender diferentes necessidades. Seu desafio é criar um código que associe os serviços de armazenamento do Azure com suas respectivas descrições. O objetivo é mapear cada serviço de armazenamento para a sua funcionalidade principal, conforme fornecido.

### **Entrada**

A entrada para o desafio consiste em um serviço de armazenamento do Azure para o qual você deve retornar a descrição correspondente. Os seguintes tipos de armazenamento são válidos para este desafio:

- `"Blob do Azure"`
- `"Disco do Azure"`
- `"Fila do Azure"`
- `"Arquivos do Azure"`
- `"Tabelas do Azure"`

### **Saída**

A saída esperada é a descrição associada ao serviço de armazenamento fornecido como entrada. Seguem as saídas possíveis, **listadas aleatoriamente**, para que você possa analisar e associar corretamente:

- `"Armazenamento de dados estruturados não relacionais em tabelas"`
- `"Armazenamento de alto desempenho para máquinas virtuais"`
- `"Armazenamento de arquivos compartilhados acessíveis por meio de SMB”`
- `"Armazenamento de mensagens para comunicação entre aplicações"`
- `"Armazenamento de arquivos grandes e não estruturados"`

```python
# Recebe a Entrada do usuário e armazena na variável "entrada"
entrada = input()

# Função responsável por receber um serviço de armazenamento e retornar sua respectiva descrição.
def identificar_servico_armazenamento(servico):
	if servico == "Arquivos do Azure":
			return "Armazenamento de arquivos compartilhados acessíveis por meio de SMB"	
	elif servico == "Blob do Azure":
	    return "Armazenamento de arquivos grandes e não estruturados
	elif servico == "Fila do Azure":
	    return "Armazenamento de mensagens para comunicação entre aplicações   	    	
	elif servico == "Tabelas do Azure":
	    return "Armazenamento de dados estruturados não relacionais em tabelas"  
	elif servico == "Disco do Azure":
	    return "Armazenamento de alto desempenho para máquinas virtuais"
    
print(identificar_servico_armazenamento(entrada))
```

## **Associando Recursos de Identidade, Acesso e Segurança**

### **Descrição**

No Microsoft Azure, identidade, acesso e segurança são fundamentais para proteger recursos e gerenciar quem tem acesso a eles. Seu desafio é criar um código que associe as ferramentas e serviços de identidade, acesso e segurança do Azure com suas respectivas descrições. O objetivo é identificar e mapear corretamente cada ferramenta para sua função principal na segurança e gerenciamento de identidades.

### **Entrada**

A entrada para o desafio consiste em uma ferramenta ou serviço de identidade, acesso e segurança do Azure para o qual você deve retornar a descrição correspondente. Os seguintes serviços e ferramentas são válidos para este desafio:

- `"Microsoft Entra ID"`
- `"Multi-Factor Authentication"`
- `"Azure Role-Based Access Control"`
- `"Azure Security Center"`
- `"Azure Key Vault"`

### **Saída**

A saída esperada é a descrição associada ao serviço ou ferramenta fornecida como entrada. Seguem as saídas possíveis, **listadas aleatoriamente**, para que você possa analisar e associar corretamente:

- `"Possibilita um gerenciamento de acesso refinado dos recursos"`
- `"Permite armazenar e acessar segredos de maneira segura"`
- `"Serviço de gerenciamento de identidades e acessos"`
- `"Proporciona uma camada adicional de segurança"`
- `"Oferece visibilidade e controle sobre a segurança dos recursos"`

```python
# Recebe a Entrada do usuário e armazena na variável "entrada"
entrada = input()

# Função responsável por receber um serviço ou ferramenta e retornar sua respectiva descrição.
def associar_recurso(recurso):
	if recurso == "Azure Role-Based Access Control":
			return "Possibilita um gerenciamento de acesso refinado dos recursos"	
	elif recurso == "Microsoft Entra ID":
	    return "Serviço de gerenciamento de identidades e acessos"
	elif recurso == "Multi-Factor Authentication":
	    return "Proporciona uma camada adicional de segurança"
	elif recurso == "Azure Key Vault":
	    return "Permite armazenar e acessar segredos de maneira segura"
	elif recurso == "Azure Security Center":
			return "Oferece visibilidade e controle sobre a segurança dos recursos"

print(associar_recurso(entrada))
```