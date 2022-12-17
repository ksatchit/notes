Area             |Components                       |Source                                           |Maintainers                                 |Reviewers|
-----------------|---------------------------------|-------------------------------------------------|--------------------------------------------|-------- |
control-plane    |chaos-manager                    |graphql-server                                   |@amityt, @Jonsy13, @rajdas98                 |@gdsoumya, @Saranya-jena, @SarthakJain26|
control-plane    |chaos-dashboard                  |frontend, component-library                       |@arkajyotiMukherjee, @S-ayanide            |@amityt, @SahilKr24, @hrishavjha|
execution-plane  |subscriber, event-tracker        |cluster-agents                                   |@gdsoumya, @rajdas98, @SarthakJain26         |@amityt, @Jonsy13, @ispeakc0de, @Adarshkumar14         |
execution-plane  |litmus-core                      |chaos-operator, chaos-runner, elves, chaos-exporter |@ksatchit, @ispeakc0de                   |@uditgaurav, @neelanjan          |   
chaos-experiments|experiment-lib, chaoshub         |litmus-go, test-tools, chaos-charts              |@uditgaurav, @ispeakc0de, @ksatchit, @Vr00mm| @neelanjan00, @Adarshkumar14, @avaakash     |
chaos-plugins    |cli, plugin infra                |litmusctl                                        |@Saranya-jena, @SarthakJain26               |@Jonsy13, @ajeshbaby, @rajdas98         | 
chaos-sdk        |go/pythion/anisble sdk           |litmus-go,litmus-python,litmus-ansible           |@oumkale, @ispeakc0de, @ksatchit            |@neelanjan00, @avaakash, @uditgaurav         | 
e2e              |e2e-suite, e2e-dashboard         |litmus-e2e                                       |@uditgaurav, @Jonsy13                       |@neelanjan00, @S-ayanide, @avaakash         |
integrations     |CI/CD plugins, wrappers          |chaos-ci-lib, gitlab-templates, github-actions   |@uditgaurav, @ksatchit                    |@ispeakc0de, @Adarshkumar14         | 
helm-charts      |control-plane, agent, experiments|litmus-helm                                      |@Jasstkn, @ispeakc0de, @rajdas98, @Jonsy13             |@ksatchit, @uditgaurav         |
documentation    |platform-docs, experiment-docs   |litmus-docs, mkdocs                              |@neelanjan00, @umamukkara, @ispeakc0de     |@ksatchit, @ajeshbaby, @amityt, @uditgaurav         |
websites         |project website, chaoshub, documentation  |litmus-website, charthub, litmus-docs   |@umamukkara, @arkajyotiMukherjee, @S-ayanide    |@SahilKr24, @hrishavjha, @ajeshbaby        |

