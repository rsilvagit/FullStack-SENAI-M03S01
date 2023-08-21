# FullStack-SENAI-M03S01
Exercícios DockerPS C:\Users\arbos\OneDrive\Rafael Pessoal\documentos\TI\Floripa Mais Tec\M03S01\FullStack-SENAI-M03S01\ex4-dockerfile> docker-compose up
[+] Running 14/1
 ✔ db 13 layers [⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿]      0B/0B      Pulled                                                                                                       46.0s 
[+] Running 3/3
 ✔ Network ex4-dockerfile_default  Created                                                                                                                    1.0s 
 ✔ Container ex4-dockerfile-db-1   Created                                                                                                                   10.1s 
 ✔ Container ex4-dockerfile-app-1  Created                                                                                                                    4.5s 
Attaching to ex4-dockerfile-app-1, ex4-dockerfile-db-1
ex4-dockerfile-db-1   | Error: Database is uninitialized and superuser password is not specified.
ex4-dockerfile-db-1   |        You must specify POSTGRES_PASSWORD to a non-empty value for the
ex4-dockerfile-db-1   |        superuser. For example, "-e POSTGRES_PASSWORD=password" on "docker run".
ex4-dockerfile-db-1   | 
ex4-dockerfile-db-1   |        You may also use "POSTGRES_HOST_AUTH_METHOD=trust" to allow all
ex4-dockerfile-db-1   |        connections without a password. This is *not* recommended.
ex4-dockerfile-db-1   | 
ex4-dockerfile-db-1   |        See PostgreSQL documentation about "trust":
ex4-dockerfile-db-1   |        https://www.postgresql.org/docs/current/auth-trust.html
ex4-dockerfile-db-1   | 
ex4-dockerfile-app-1  | The command could not be loaded, possibly because:
ex4-dockerfile-app-1  |   * You intended to execute a .NET application:
ex4-dockerfile-app-1  |       The application 'Ex4-Dockerfile.ddl' does not exist.
ex4-dockerfile-app-1  |   * You intended to execute a .NET SDK command:
ex4-dockerfile-app-1  |       No .NET SDKs were found.
ex4-dockerfile-app-1  | 
ex4-dockerfile-app-1  | Download a .NET SDK:
ex4-dockerfile-app-1  | https://aka.ms/dotnet/download
ex4-dockerfile-app-1  | 
ex4-dockerfile-app-1  | Learn about SDK resolution:
ex4-dockerfile-app-1  | https://aka.ms/dotnet/sdk-not-found
ex4-dockerfile-app-1  | 
ex4-dockerfile-db-1 exited with code 1
ex4-dockerfile-db-1   | Error: Database is uninitialized and superuser password is not specified.
ex4-dockerfile-db-1   |        You must specify POSTGRES_PASSWORD to a non-empty value for the
ex4-dockerfile-db-1   |        superuser. For example, "-e POSTGRES_PASSWORD=password" on "docker run".
ex4-dockerfile-db-1   |
ex4-dockerfile-db-1   |        You may also use "POSTGRES_HOST_AUTH_METHOD=trust" to allow all
ex4-dockerfile-db-1   |        connections without a password. This is *not* recommended.
ex4-dockerfile-db-1   |
ex4-dockerfile-db-1   |        See PostgreSQL documentation about "trust":
ex4-dockerfile-db-1   |        https://www.postgresql.org/docs/current/auth-trust.html
ex4-dockerfile-db-1   |
ex4-dockerfile-db-1 exited with code 0
ex4-dockerfile-app-1 exited with code 145