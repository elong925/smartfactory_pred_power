# smartfactory_pred_power

~~~graphql
smartfactory_site/
  schema.sql
  app/
    main.py
    db.py
    config.py
    services/
      peaks.py
      forecast.py
  scripts/
    etl_5s_to_1m.py
    compute_contract_kw.py
    train_future_model_B.py
  dashboard/
    streamlit_app.py
  artifacts/
    model_A.pkl      # (옵션) 22피처 모델 (실시간용)
    model_B.pkl      # (필수) 미래예측용(시간+lag) 모델
~~~
