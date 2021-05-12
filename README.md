<h3 align="center">
  :hammer_and_wrench: :computer:
  <br><br>
  Desafio de Migração de Dados
</h3>

<blockquote align="center">Mostre que você domina os conceitos básicos para realizar uma migração de dados em PHP!</blockquote>

## :rocket: Sobre o Desafio:

Nesse desafio você deve desenvolver um script em PHP para migrar os dados entre dois sistemas fictícios. Os dados do sistema legado fictício foram extraídos no formato CSV e devem ser migrados para a estrutura de outro sistema fictício, em uma banco de dados MySQL (MariaDB).

## :medical_symbol: Contextualizando:

Uma clínica médica está se atualizando e trocando de sistema. Para isso, é necessário migrar os dados dos seus pacientes e agendamentos para o novo sistema que será implantado, o MedicalChallenge. Os dados dos dois sistemas estão estruturados de formas diferentes, e o seu desafio é adequar e migrar os dados do sistema legado para o novo sistema. A clínica já cadastrou seus médicos e também alguns convênios, procedimentos, pacientes e agendamentos no sistema novo.

## :computer: Estrutura do MedicalChallenge:

Felizmente você trabalha na empresa desenvolvedora do MedicalChallenge e possui conhecimento da estrutura do sistema, que é muito simples e de fácil compreensão:

![schema](https://raw.githubusercontent.com/MigrationAmpli/migration-challenge/main/MedicalChallenge_Schema.png?token=AUBQFH3GANO3QQARWGJ5M5LATQR32)

## :computer: Estrutura do Sistema Legado:

Já o sistema legado disponibilizou um backup em CSV. São duas tabelas, uma de pacientes e uma de agendamentos. Você precisa encontrar uma forma de ler, estruturar e migrar os dados para as tabelas do MedicalChallenge. **Dica:** Você pode criar uma função para transportar os dados dos arquivos CSV para um banco de dados temporário local.
