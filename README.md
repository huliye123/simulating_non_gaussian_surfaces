# Non-Gaussian Surface Simulations

**Author:** Sebastian Korsak

Special thanks to Max Pierini and his repository: https://github.com/maxdevblock/j_johnson_M, and my prof. V. Costantoudis who gave me the code in MATLAB.

The method we followed is described on the paper: *Numerical Simulation of 3D Rough Surfaces and Analysis
of Interfacial Contact Characteristics*, by Guoqing Yang, Baotong Li, Yang Wang and Jun Hong. Here we have some of the steps as are writen in this paper.

# How to use it

Import the library:

```python
import non_gaussian_surfaces as seb
```

And then type

```python
seb.SAimage_fft_2(500,3,1,3,20,20,0.9,800.0,corr=True)
```

# Results

![3D Non Gaussian Rough Surface](https://www.kaggleusercontent.com/kf/61423748/eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0..L4devM82DxraAennBlqmSg.8IB0H90ZEo4zm6bjCJBUH_W5NU7L4SdTTt6dYbBeN1lnXvr3Hwd8ruoSrcTEtqeZ12aC6XwjQnCvsDXKhGEg8oAUFDxjLY9m_gXlJWrmN3q_ZFGKLsYSxon_CPwWAoV1swVdTWD0qaksD4Iy4Ka7MM4mFIvvd_KgWVjfWA4IblYGZAoCavdtgHboJi02doKLahEerAiZ9owptWFupi0c4qOk2SkooxLIMZLRqwdPHvQo5jOnweL6Rf96hqcrFnCToMTEsLc3gqUMpGAXzOpyaF-ug9rzVwchdwk2-KEdACd7QjYmB1yvLMD4i5YWrzdWICmaNM5iLJpxfXDyDhf4rma5pGRUDU1F5M985wEwAGWcS-dC6alAAXXttMwZSqmqZ4AOygCR4HVyVt_Ac-JRoXI6mVHZmmucY89AddR-upkbKxwR-x7lwNE3PQe6zrbMFEgacjqM5EdWrrGrZaAa-kNEg4Bx1Vdfv_glWyY8fDTqKCr0f9hRb_5xed8HL15805li1eqM1NceQCR-dU81ybMUx9O6CqYtMvNjOItbokDgRG6Eqs_zbIG5mweOBlILMJYwiIiZ8iCXc1Jxzhfs5hNjARUTvqwdjjnAKw3bBSonYgfgFP_y2rsFC2g7cSXUkJSdyaItZPO-nSIbyl4B6M0yDc--Rscw5CiMEYhSal8nqdf3GDurpAou7iFvKRCX.bRhYcn5p8WclK5IjGqZC0g/__results___files/__results___7_1.png)

![Binary Image Extracted from the 3D Gaussian Surface](https://www.kaggleusercontent.com/kf/61423748/eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0..L4devM82DxraAennBlqmSg.8IB0H90ZEo4zm6bjCJBUH_W5NU7L4SdTTt6dYbBeN1lnXvr3Hwd8ruoSrcTEtqeZ12aC6XwjQnCvsDXKhGEg8oAUFDxjLY9m_gXlJWrmN3q_ZFGKLsYSxon_CPwWAoV1swVdTWD0qaksD4Iy4Ka7MM4mFIvvd_KgWVjfWA4IblYGZAoCavdtgHboJi02doKLahEerAiZ9owptWFupi0c4qOk2SkooxLIMZLRqwdPHvQo5jOnweL6Rf96hqcrFnCToMTEsLc3gqUMpGAXzOpyaF-ug9rzVwchdwk2-KEdACd7QjYmB1yvLMD4i5YWrzdWICmaNM5iLJpxfXDyDhf4rma5pGRUDU1F5M985wEwAGWcS-dC6alAAXXttMwZSqmqZ4AOygCR4HVyVt_Ac-JRoXI6mVHZmmucY89AddR-upkbKxwR-x7lwNE3PQe6zrbMFEgacjqM5EdWrrGrZaAa-kNEg4Bx1Vdfv_glWyY8fDTqKCr0f9hRb_5xed8HL15805li1eqM1NceQCR-dU81ybMUx9O6CqYtMvNjOItbokDgRG6Eqs_zbIG5mweOBlILMJYwiIiZ8iCXc1Jxzhfs5hNjARUTvqwdjjnAKw3bBSonYgfgFP_y2rsFC2g7cSXUkJSdyaItZPO-nSIbyl4B6M0yDc--Rscw5CiMEYhSal8nqdf3GDurpAou7iFvKRCX.bRhYcn5p8WclK5IjGqZC0g/__results___files/__results___7_2.png)

![Correlation Functions](https://www.kaggleusercontent.com/kf/61423748/eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0..L4devM82DxraAennBlqmSg.8IB0H90ZEo4zm6bjCJBUH_W5NU7L4SdTTt6dYbBeN1lnXvr3Hwd8ruoSrcTEtqeZ12aC6XwjQnCvsDXKhGEg8oAUFDxjLY9m_gXlJWrmN3q_ZFGKLsYSxon_CPwWAoV1swVdTWD0qaksD4Iy4Ka7MM4mFIvvd_KgWVjfWA4IblYGZAoCavdtgHboJi02doKLahEerAiZ9owptWFupi0c4qOk2SkooxLIMZLRqwdPHvQo5jOnweL6Rf96hqcrFnCToMTEsLc3gqUMpGAXzOpyaF-ug9rzVwchdwk2-KEdACd7QjYmB1yvLMD4i5YWrzdWICmaNM5iLJpxfXDyDhf4rma5pGRUDU1F5M985wEwAGWcS-dC6alAAXXttMwZSqmqZ4AOygCR4HVyVt_Ac-JRoXI6mVHZmmucY89AddR-upkbKxwR-x7lwNE3PQe6zrbMFEgacjqM5EdWrrGrZaAa-kNEg4Bx1Vdfv_glWyY8fDTqKCr0f9hRb_5xed8HL15805li1eqM1NceQCR-dU81ybMUx9O6CqYtMvNjOItbokDgRG6Eqs_zbIG5mweOBlILMJYwiIiZ8iCXc1Jxzhfs5hNjARUTvqwdjjnAKw3bBSonYgfgFP_y2rsFC2g7cSXUkJSdyaItZPO-nSIbyl4B6M0yDc--Rscw5CiMEYhSal8nqdf3GDurpAou7iFvKRCX.bRhYcn5p8WclK5IjGqZC0g/__results___files/__results___7_3.png)
