# big-federated-graphs

Examples of large federated GraphQL schemas.

There are two complete examples of large federated graphs in the schemas directory: edge0 and edge1.

Each "edge" directory contains a `subgraphs` directory of individual service schemas. The subgraphs, when composed together using a compatible composition algorithm, form a complete federated graph which is found in the root directory of the repository as `composed.graphql`.

These subgraphs are compatible with a variant of the original (v1) Apollo Federation Specification which incorporates some features of the v2 specification.
