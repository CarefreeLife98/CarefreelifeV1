# CarefreelifeV1
Toy project to learn Spring Boot

Before execute this program, 
please make sure that your h2db table is already prepared by these codes.

<h2db table>

drop table member if exists cascade;
create table member (
id integer not null default 0,
membername char (30),
tel char(30),
primary key (id)
);
