# filmarate_base
filmarate project database schema

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://github.com/Pawel070/filmarate_base/blob/26338744065d38f187ae6c1ff92725aeaa349933/Filmarate_dark.png">
  <source media="(prefers-color-scheme: light)" srcset="https://github.com/Pawel070/filmarate_base/blob/67fe623dd959771fccace54e922b89ebb0d31ee4/Filmarate_light.png">
  <img alt="Filmarate project database schema" src="https://github.com/Pawel070/filmarate_base/blob/eb937f2ce7e967a10b9c7db34a2471fed5c6edfb/Filmarate.png">
</picture>

## base structure in the format PostgreSQL https://github.com/Pawel070/filmarate_base/blob/8b03e4aebd4e5edaef98f6f20fd0430476ab445f/Filmarate.sql
## additional data types used in base listed below and in the file https://github.com/Pawel070/filmarate_base/blob/3db4f58daef7cb24b6d901233d98a0a5ba3ff2d3/Enum.txt

<!-- Enum pawel.genre_status {               -->
<!-- COMEDY                                  -->
<!-- DRAMA                                   -->
<!-- CARTOON                                 -->
<!-- TRILLER                                 -->
<!-- DOCUMENTARY                             -->
<!-- HITMAN                                  -->
<!-- }                                       -->

<!-- Enum pawel.rate_status {                -->
<!-- G                                       -->
<!-- PG                                      -->
<!-- PG14                                    -->
<!-- R                                       -->
<!-- NC17                                    -->
<!-- }                                       -->

<!-- Enum ecommerce.products_status {        -->
<!-- out_of_stock                            -->
<!-- in_stock                                -->
<!-- running_low [note: "less than 20"]      -->
<!-- }                                       -->
