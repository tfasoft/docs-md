# Res codes

If the request be successful, you get 200. Else anything that API returns to you, you need to check the `resCode`.

## Codes

Here are the res codes you have to know.

| HTTP Code | ResCode | Details                              |
| :-------- | :------ | :----------------------------------- |
| 500       | 0       | Service unavailable                  |
| 401       | 1       | Provider access token is not valid   |
| 404       | 2       | User access token is not valid       |
| 403       | 3       | Provider doesn't have enoght credits |
| 400       | 4       | Provider account is not active       |
| 400       | 5       | Service is not active                |
| 403       | 6       | IP not valid                         |
