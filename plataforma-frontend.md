# Plataforma Frontend

**Data:** 22/02/2024

## Contexto
Plataforma/Famework frontend mobile utilizado no desenvolvimento do produto Rota Regional.

## Decisão
Será utilizada a biblioteca Javascript para desenvolvimento multiplataforma, o React Native.

- **Multiplataforma:**  Com o React Native, é possível compartilhar uma porção significativa do código entre as versões iOS e Android de um aplicativo. Os componentes principais podem ser reaproveitados, enquanto módulos específicos da plataforma podem ser incorporados conforme necessário.
- **Acesso a Recursos Nativos:** O React Native permite o acesso a APIs nativas dos dispositivos, possibilitando a integração com recursos específicos de cada plataforma.
- **Atualizações Dinâmicas:** Uma característica interessante é a capacidade de atualizar partes do aplicativo sem passar pela aprovação nas lojas de aplicativos.

## Consequências

- **Desempenho:** Embora o React Native ofereça bom desempenho, especialmente para aplicativos com interfaces de usuário complexas, algumas partes do aplicativo podem exigir módulos nativos para otimização.
- **Acesso a Recursos Nativos Específicos:** Embora o React Native ofereça bom desempenho, especialmente para aplicativos com interfaces de usuário complexas, algumas partes do aplicativo podem exigir módulos nativos para otimização.
- **Atualizações de Plataforma:** Quando uma nova versão de uma plataforma é lançada (por exemplo, uma nova versão do iOS ou Android), pode haver um atraso entre a atualização da plataforma e a compatibilidade total do React Native com a nova versão. Isso pode resultar em incompatibilidades ou a necessidade de aguardar atualizações do React Native.