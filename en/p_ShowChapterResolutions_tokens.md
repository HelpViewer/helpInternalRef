**(array)**

list of tokens for this process run.

| Token | Result |
|---|---|
| TOKEN_NOLOADDATA | Loading of data (**pTRLoadData:-load** plugin is skipped as the data has been passed externally to given request) |
| TOKEN_NONOTFOUNDMSG | Message **MSG_PATH_NOT_FOUND_IN_ARCH** in chapter output is not applied with this token when storage chapter data are not found. Used for technical/internal dynamic pages (e.g. this **ObjectExplorer**) |

By tokens.push you can insert another token to your processing. In any next processing phases of **pTopicRenderer** you can check for (non)existence of token and provide an alternative behavior for that case.
