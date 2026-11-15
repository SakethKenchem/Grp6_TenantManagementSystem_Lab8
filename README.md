# Tenant Management System

An Android app for landlords to record tenants, see total rent, and call tenants.

## Download
Latest APK: see **Releases** on the right of this page.

## Features
- Register and log in
- Dashboard with number of tenants and total rent
- Add tenants and view all tenants (saved with Room)
- Call a tenant, options menu and navigation drawer

## Architecture
ui/    Activities, Fragments and TenantViewModel (UI layer)
data/  Tenant, TenantDao, TenantDatabase, TenantRepository (data layer)

Screens → TenantViewModel (LiveData) → TenantRepository → Room

## Team

| Stage | Member | Admission No. | Pull request |
|---|---|---|---|
| 1 Lead | Saketh Kenchem | 152324 | (link) |
| 2 ViewModel | Andrew Mutero | 150736 | ([link](https://github.com/SakethKenchem/Grp6_TenantManagementSystem_Lab8/pull/1)) |
| 3 Room | Mark Kipruto | 169386 | ([link](https://github.com/SakethKenchem/Grp6_TenantManagementSystem_Lab8/pull/3)) |
| 4 Screens | Lewis Kamunjeru | 155669 | ([link](https://github.com/SakethKenchem/Grp6_TenantManagementSystem_Lab8/pull/2)) |
| 5 Data integration | Kumaylali Viqarhussein Murji | 193642 | ([link](https://github.com/SakethKenchem/Grp6_TenantManagementSystem_Lab8/pull/4)) |
| 6 Release | Saketh Kenchem | 152324 | ([link](https://github.com/SakethKenchem/Grp6_TenantManagementSystem_Lab8/pull/5)) |
