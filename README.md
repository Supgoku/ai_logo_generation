# Improving Logo Generation by Approximating the Logo Design Process
Logo creation is a complex and expansive problem for artificial intelligence. There are several complications, some technical such as lack of hierarchy and lack of continuous space, as well as design complications, such as the difficulty of selecting a typeface or color. However, given that producing a logo is time- and resource-intensive, using artificial intelligence to expedite the process is an attractive challenge. There are currently three types of logo generation AI: one set asks the user to select from a set of icons, colors, and typefaces and iterates over layouts; these designs are aesthetically pleasing, but lack content or meaning, and the user is tasked with making most of the choices. The second set uses a collection of images to synthesize a new image; the resulting graphics are often non-representational and low-quality, and the logos don’t include text. A third method relies on pre-designed logos and focuses on style transfer; this makes for visually interesting logos, but relies on the user inputting a base logo. We propose a new type of logo generation AI that better approximates the logo design process by asking the user to input attributes they would like to impose on the logo. We use these attributes to produce a content and a style image from pre-trained datasets, and we use synonym expansion if we don’t get a direct match. Using style transfer, we produce an image that we then combine with text. By following a simplified version of the logo design process, the result is a visually pleasing logo that is usable and recognizable, and includes meaning.

## Copyright
Some of the code in this repo is from https://github.com/gttugsuu/Constrained-Neural-Style-Transfer-for-Decorated-Logo-Generation/ aka CNST.
See cnst_LICENSE.txt and cnst_README.txt for license and readme for the original work.
Code from CNST is marked with a notice at the top of the source files.

## Notes

* Notes from getting the code from the constrained neural style transfer paper to run are at: https://gist.github.com/ranton256/61abed764dfa31821781e5d695f92893
* 
## References

* Agustsson, E.; Sage, A.; Timofte; Van Gool, L. 2017. Logo Synthesis and Manipulation with Clustered Generative Adversarial Networks. Ithaca, NY: Cornell University. arXiv:1712.04407v1.
* Atarsaikhan, G.; Iwana, B.K.; and Uchida, S. 2018. Constrained Neural Style Transfer for Decorated Logo Generation. Ithaca, NY: Cornell University. arXiv:1803.00686v2.
* Bethge, M; Ecker, A.S.; and Gatys, A.L. 2016. A Neural Algorithm of Artistic Style. Journal of Vision 16(12): 326-. arXiv:1508.06576v2.
* Birdsall, C, 2008. Corporate Identity. The Essential Principles of Graphic Design. Edited by Debbie Millman. Cincinnati, Ohio: How Books.
* Chang, A, et al, 2015. ShapeNet: An Information-Rich 3D Model Repository. Stanford University --- Princeton University --- Toyota Technological Institute at Chicago.
* Chang A.; Hanrahan, P; Savva, M. 2015. Semantically-Enriched 3D Models for Common-sense Knowledge. CVPR 2015 Workshop on Functionality, Physics, Intentionality and Causality.
* Fellbaum, C. 1998. WordNet: An Electronic Lexical Database. Cambridge, MA: MIT Press
* Ginger, E.M., and Spiekermann, E. 2003. Stop Stealing Sheep & Find Out How Type Works. Berkeley, California: Peachpit Press.
* Mino, A., and Spanakis, G. 2018. LoGAN: Generating Logos with a Generative Adversarial Neural Network Conditioned on Color. In proceedings of the 17th IEEE International Conference on Machine Learning and Applications. arXiv:1810.10395v1.
* Napoles, V, 1988.Corporate Identity Design. New York: John Wiley & Sons, Inc.
Oeldorf, Cedric and Spanakis, Gerasimos. (2019). LoGANv2: Conditional Style-Based Logo Generation with Generative Adversarial Networks. 462-468. 10.1109/ICMLA.2019.00086.
* Russakovsky, O, et al, 2015. ImageNet Large Scale Visual Recognition Challenge. International Journal of Computer Vision (IJCV) 115(3): 211-252. 10.1007/s11263-015-0816-y
* Wheeler, A. 2003. Designing Brand Identity. Hoboken, New Jersey: John Wiley & Sons. 



