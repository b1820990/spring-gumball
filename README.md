# spring-gumball ci/cd example

##Part 1 (CI)
-Successful trigger of the action
![pt1](https://user-images.githubusercontent.com/54514627/144162798-b5d8afd6-58f6-464c-8cdc-2b9a13f2d045.PNG)

-All workflows after triggering the action
![commit1](https://user-images.githubusercontent.com/54514627/144164076-f683ae69-0985-4c18-be0d-b752f746a8f3.PNG)


##Part 2 (CD)
-GCP Service account with key
![pt2_IAM](https://user-images.githubusercontent.com/54514627/144163018-3e204487-a16a-4d08-9f7d-d61107d969d1.PNG)

-GCP SA key
![pt2_keys_IAM](https://user-images.githubusercontent.com/54514627/144163098-7076a1ca-b8d5-407e-8ca7-c341617f62c7.PNG)

-Github Action Secrets
![pt2_secrets](https://user-images.githubusercontent.com/54514627/144163265-a9aa095d-faf7-48b6-a9c4-c3d5e056869a.PNG)

-Creating GKE Cluster
![cluster](https://user-images.githubusercontent.com/54514627/144163380-fa19d64b-962e-4e54-af0e-b4ec9d75be67.PNG)

-Making release
![pt2_release](https://user-images.githubusercontent.com/54514627/144163453-72fa8d73-65f6-49c5-b1d0-ed2ebfdbbf6b.PNG)

-Opening release
![pt2_preRelease](https://user-images.githubusercontent.com/54514627/144163492-a820dc0b-c79c-4300-99f2-3af92a856823.PNG)

-Successful build of action
![pt2_gkeGit](https://user-images.githubusercontent.com/54514627/144164280-c09e34b4-e3aa-4689-97bc-7e8606bdbd7e.PNG)

-All Workflows on github
![pt2_allWkFlows](https://user-images.githubusercontent.com/54514627/144163556-72f544c8-ce6b-434f-b2e2-92238c641606.PNG)

-Successful build and deploy
![pt2_postRelease](https://user-images.githubusercontent.com/54514627/144163608-8c68252b-a658-4cea-83d6-8fb333b3871c.PNG)

-GKE Deployment
![pt2_GKEWkLoads](https://user-images.githubusercontent.com/54514627/144163875-9efcd40d-e6c9-478c-a7c6-b2bb365091c1.PNG)

-GKE Service
![pt2_GKEServices](https://user-images.githubusercontent.com/54514627/144163942-33d1b515-f9f1-41d8-b0da-50e27a666fac.PNG)

-GKE Ingress
![pt2_ingress](https://user-images.githubusercontent.com/54514627/144163982-0b1ecc46-4d95-4d90-a2a7-1334784231fa.PNG)

-Running the application
![pt2_running](https://user-images.githubusercontent.com/54514627/144164006-bf357c68-1a7c-48e1-95c0-c285bf5aa9e8.PNG)
