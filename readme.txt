create table user_profile
(
  id int,
  name VARCHAR(128) not null,
  profile_image   VARCHAR(128) not null,
  job_title  BIGINT not null,
  description  text(128) not null
) ;
