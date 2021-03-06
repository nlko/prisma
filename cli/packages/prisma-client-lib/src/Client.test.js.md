# Snapshot report for `dist/Client.test.js`

The actual snapshot is saved in `Client.test.js.snap`.

Generated by [AVA](https://ava.li).

## deep related type

> Snapshot 1

    `{␊
      user {␊
        posts {␊
          content␊
        }␊
      }␊
    }␊
    `

## embedded type

> Snapshot 1

    `{␊
      user {␊
        id␊
        posts {␊
          content␊
        }␊
      }␊
    }␊
    `

## nested mbedded type

> Snapshot 1

    `{␊
      user {␊
        id␊
        posts {␊
          content␊
          meta {␊
            meta␊
          }␊
        }␊
      }␊
    }␊
    `

## related type

> Snapshot 1

    `{␊
      user {␊
        id␊
      }␊
    }␊
    

## nested args

> Snapshot 1

    `query ($where: PostInput!) {␊
      post(where: $where) {␊
        id␊
        title␊
        content␊
      }␊
    }␊
    `

## top level args

> Snapshot 1

    `query ($where: PostInput!) {␊
      post(where: $where) {␊
        id␊
        title␊
        content␊
      }␊
    }␊
    

## automatic non-scalar sub selection

> Snapshot 1

    `query ($where: UserWhereInput) {␊
      users(where: $where) {␊
        __typename␊
      }␊
    }␊
    

## automatic non-scalar sub selection for relation

> Snapshot 1

    `query ($where: HouseWhereInput) {␊
      house(where: $where) {␊
        user {␊
          __typename␊
        }␊
      }␊
    }␊
    `