# medallion_model_data
Repositório para criar um modelo de gerenciamento e ingestão de dados na AWS utilizando três camadas: 

Na primeira camada , a camada BRONZE, serão armazenados os dados em seu formato bruto, sem tratamento prévio.
Na segunda camada, a camada SILVER, os dados vindos da camada BRONZE serão tratados e limpos.
Na terceira camada, a camada GOLD, teremos os dados prontos para serem consumidos por ferramentas de analytics, como Power BI, Streamlit, Quick Sight ou afins.
