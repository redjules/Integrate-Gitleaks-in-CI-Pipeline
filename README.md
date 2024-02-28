# Integrate Gitleaks in CI Pipeline

![Screenshot 2024-02-28 at 18 51 46](https://github.com/redjules/Integrate-Gitleaks-in-CI-Pipeline/assets/106017493/12e93803-4221-4cd4-8110-5e965f0788c1)


![Screenshot 2024-02-28 at 18 53 36](https://github.com/redjules/Integrate-Gitleaks-in-CI-Pipeline/assets/106017493/ab020050-458d-4bd7-8946-501bfaa91267)


![Screenshot 2024-02-28 at 18 54 13](https://github.com/redjules/Integrate-Gitleaks-in-CI-Pipeline/assets/106017493/3964bbfb-8c3d-4874-95c6-514ca0ceff91)


![Screenshot 2024-02-28 at 18 54 30](https://github.com/redjules/Integrate-Gitleaks-in-CI-Pipeline/assets/106017493/a13de15b-5890-466d-aa99-dda5b5671271)

We will install Gitleaks via Docker Image:

![Screenshot 2024-02-28 at 18 55 46](https://github.com/redjules/Integrate-Gitleaks-in-CI-Pipeline/assets/106017493/3b2ce508-b4d5-457b-be7f-0db1ef62ef13)

we pull the imageb from Docker:

![Screenshot 2024-02-28 at 19 03 33](https://github.com/redjules/Integrate-Gitleaks-in-CI-Pipeline/assets/106017493/0afca987-ef10-4505-a6cd-d0a55fed9337)

we got 9 leaks:

![Screenshot 2024-02-28 at 19 04 20](https://github.com/redjules/Integrate-Gitleaks-in-CI-Pipeline/assets/106017493/a16356ee-046c-4bb7-98ac-8f677dd51e24)

here are the details:

![Screenshot 2024-02-28 at 19 05 18](https://github.com/redjules/Integrate-Gitleaks-in-CI-Pipeline/assets/106017493/60037865-8646-4027-b0cd-281fc8c856f1)

Now we will integrate it in the pipeline:

![Screenshot 2024-02-28 at 19 10 15](https://github.com/redjules/Integrate-Gitleaks-in-CI-Pipeline/assets/106017493/945f5b0b-62e7-49ec-bb07-9a77de0616a8)

![Screenshot 2024-02-28 at 19 11 44](https://github.com/redjules/Integrate-Gitleaks-in-CI-Pipeline/assets/106017493/92918bef-7df4-4c09-b55d-04ead53f327e)

![Screenshot 2024-02-28 at 19 14 03](https://github.com/redjules/Integrate-Gitleaks-in-CI-Pipeline/assets/106017493/2010f5f4-bed3-4028-bf64-6b13e23173d7)


![Screenshot 2024-02-28 at 19 16 59](https://github.com/redjules/Integrate-Gitleaks-in-CI-Pipeline/assets/106017493/0e2f159a-1d62-4341-bb37-a04a5611d697)


![Screenshot 2024-02-28 at 19 17 15](https://github.com/redjules/Integrate-Gitleaks-in-CI-Pipeline/assets/106017493/2687d23f-db11-4135-9897-d0d0b513389c)

![Screenshot 2024-02-28 at 19 18 11](https://github.com/redjules/Integrate-Gitleaks-in-CI-Pipeline/assets/106017493/d22ecc46-a815-4845-a9eb-1eaa2332df21)


![Screenshot 2024-02-28 at 19 20 05](https://github.com/redjules/Integrate-Gitleaks-in-CI-Pipeline/assets/106017493/b9e4132c-079f-415f-b8ae-e2c2f78248b4)


![Screenshot 2024-02-28 at 19 20 52](https://github.com/redjules/Integrate-Gitleaks-in-CI-Pipeline/assets/106017493/b9d63b1d-168f-4d73-bebd-ce2205406d06)

![Screenshot 2024-02-28 at 19 21 08](https://github.com/redjules/Integrate-Gitleaks-in-CI-Pipeline/assets/106017493/c5431c24-6d46-4ff6-9240-4019ae4613ee)


![Screenshot 2024-02-28 at 19 21 50](https://github.com/redjules/Integrate-Gitleaks-in-CI-Pipeline/assets/106017493/9149ea82-df54-4484-a5d2-4d7d86ad9854)

![Screenshot 2024-02-28 at 19 26 51](https://github.com/redjules/Integrate-Gitleaks-in-CI-Pipeline/assets/106017493/846864c3-ef5f-46d2-b98a-979687ef607d)

we make the hook executable:

![Screenshot 2024-02-28 at 19 27 52](https://github.com/redjules/Integrate-Gitleaks-in-CI-Pipeline/assets/106017493/00b921f6-493d-4ba7-bc0c-69052e681310)

we commit:

![Screenshot 2024-02-28 at 19 29 10](https://github.com/redjules/Integrate-Gitleaks-in-CI-Pipeline/assets/106017493/334fc0dd-3f80-43b5-bb1a-35c37084c766)

and gitleaks gets activated and tells us about the leaks found:

![Screenshot 2024-02-28 at 19 29 42](https://github.com/redjules/Integrate-Gitleaks-in-CI-Pipeline/assets/106017493/f42bb7b7-adb7-4a4b-abd3-525ea4cbf381)

we want to shift securtiy as much to the left as possible!

![Screenshot 2024-02-28 at 19 30 40](https://github.com/redjules/Integrate-Gitleaks-in-CI-Pipeline/assets/106017493/5a11b939-11a3-4ba9-95be-4e61297600a4)

