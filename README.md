# Optimization Dashboard

Optimizing Jaú-Supermarkets routes mathematically using non-linear and discrete optimization, hybrid framework

One can use this project by following the steps:

1) Clone repo and build a virtual environment with requirements and dependencies
2) Modify jau_sao_carlos_store.csv depot line to change depot location as user want to
3) run models/matrix_builder.py to automatically build matrix file inside the data folder
4) run dashboard/app.py to build interface locally:
   - move to repo (cd jau-optim) and with activated *venv* run: streamlit run jau_routes/dashboard/app.py
   - should be able to open dashboard

![](pics/1.png)

![](pics/2.png)

![](pics/3.png)

![](pics/4.png)
