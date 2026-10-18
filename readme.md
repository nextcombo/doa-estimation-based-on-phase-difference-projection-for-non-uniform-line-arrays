# DOA Estimation Based on Phase Difference Projection for Non-uniform Line Arrays [with MATLAB Code]

Introduction  
Direction of Arrival (DOA) estimation is an important topic in various applications such as wireless sensor networks [1], indoor positioning and tracking [2], radar [3], and wireless communication [4]. In recent years, many DOA estimation methods have been proposed, mainly focusing on uniform linear array (UWB) structures. On the other hand, the use of non-uniform linear arrays (NULA) has also become popular. The configuration of NULA is usually used to expand the aperture of the array, thereby improving the DOA resolution of the array.  
In this paper, we focus on single-source DOA estimation using NULA. This situation is triggered by millimeter wave/THz multi-input multi-output (MIMO) communication environments. In these systems, flexible arrays are adopted to reduce high computational and hardware costs (see switch-based MIMO [7] and subarray array (AOSA) structure [8]). When applying antenna/subarray selection algorithms, a NULA structure will be formed. Besides the NULA structure, analog beamforming in these systems can reduce multipath and provide dominant line-of-sight (LOS) signals [9]. Therefore, single-source DOA estimation is an important issue in millimeter wave/THz MIMO systems.  
The DOA estimation problem can be formulated as the optimization of a cost function over feasible DOA ranges. Typically, the process requires evaluating the entire DOA range cost function and searching for its optimal value. Maximum likelihood estimation (MLE) [10] and MUSIC [11] are two widely used methods, which are examples of this approach. However, this method has the disadvantage that the search process increases computational complexity, especially when high spatial resolution is required.
Time delay estimation is a rapid alternative to DOA estimation, which can directly produce DOA estimates without the need for grid search [12]. The linear relationship between time delay and phase difference allows using phase difference measurements for DOA estimation. Based on phase difference DOA estimation has been reported as an effective method for multi-carrier signals [13] and [14]. However, based on phase difference DOA estimation suffers from occurrence of phase wrapping [15] and [16]. 
The issue of phase wrapping can be addressed by utilizing frequency diversity available in multi-frequency signals or spatial diversity in single-frequency scenarios [17]. Spatial diversity phase expansion methods include [15], and recent off-line methods such as 2Q-order diversity [18] and two-step offset correction [19]. These methods have the main disadvantage of requiring specialized antenna setups. Moreover, these methods tend to be sensitive to phase noise effects. 
This paper proposes a phase difference projection (PDP) method for DOA estimation using non-uniform linear arrays. We utilize a new concept, wrap phase difference pattern (WPDP). Experimental results show that this method can easily be applied to any linear array structure with three or more sensors. Simulation results validate the good compromise between computational complexity and DOA estimation performance of the proposed method. 
Article illustration  
Conclusion  
We propose a wave arrival direction estimation algorithm based on phase difference projection (PDP). This algorithm projects the phase difference observations between antenna pairs onto predefined hyperplanes determined by the array geometry. Based on this projection, DOA estimation can be realized in a simple and computationally efficient manner. Simulation results demonstrate that the algorithm effectively matches maximum likelihood estimation while maintaining a significant computational complexity advantage. 
End

## Images

![(DOA Estimation)Non-uniform Line Array DOA Estimation Based on Phase Difference Projection [with MATLAB Code]](01.jpg)
![(DOA Estimation)Non-uniform Line Array DOA Estimation Based on Phase Difference Projection [with MATLAB Code]](02.jpg)
![(DOA Estimation)Non-uniform Line Array DOA Estimation Based on Phase Difference Projection [with MATLAB Code]](03.jpg)
![(DOA Estimation)Non-uniform Line Array DOA Estimation Based on Phase Difference Projection [with MATLAB Code]](04.jpg)

<!-- PAYMENT_BLOCK -->

## Get this dataset

- Payment link (Stripe): [Buy now](https://buy.stripe.com/3cs8yP7sY87d0vu9AB)
- Payment QR code: ![Payment QR code](pay.png)

<!-- /PAYMENT_BLOCK -->
