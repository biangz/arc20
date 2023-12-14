<template>
    <div class="homepage-container">
        <div class="section01 px-4 lg:px-10">
            <div class="flex flex-col lg:flex-row items-start justify-between gap-x-8 relative z-[2] lg:w-full">
                <div class="max-w-xl">
                    <h1 class="text-base">DIS Chain: Innovative PoW Public Chain Merging AI and
                        MEME Culture</h1>
                    <p class="mt-4 text-xs font-cr">Initiating a New Era of Blockchain and Artificial Intelligence.</p>
                    <!-- <a-button class="bg-white mt-8 px-2 text-sm">Get Start</a-button> -->
                    <a-button class="mt-4" type="primary">Get Start</a-button>
                </div>
                <img class="banner-image text-xs w-[13rem] hidden lg:block" src='../assets/images/pic-banner.png' />
            </div>
            <img class="bg-image" src="../assets/images/bg-l.png" />
        </div>

        <!-- <div class="section02 px-4 lg:px-40 py-16 relative">
            <div class="relative z-[2] text-center">
                <h1 class="text-sm font-cr">WHO WE ARE</h1>
                <p class="text-3xl font-cm mt-8 tracking-wider">DIS Chain is an innovative PoW (Proof of Work) public
                    chain that highly values the integration of MEME culture and AI computational power, creating a
                    high-efficiency and decentralized blockchain ecosystem.</p>
                <button
                    class="bg-[#1559ed] mx-auto text-white mt-12 px-6 py-2 font-cr text-sm flex items-center rounded-sm">
                    <span>Learn More</span>
                    <img class="w-4 ml-2" src="../assets/images/arrow-right.svg" />
                </button>
            </div>
            <img class="absolute right-0 w-[20rem] top-0" src="../assets/images/section-02-l.png" />
            <img class="absolute left-0 w-[20rem] top-0" src="../assets/images/section-02-r.png" />
        </div> -->

        <div class="section03 px-4 lg:px-10 py-20 relative overflow-hidden">
            <div class="relative z-[2]">
                <h1 class="text-base font-cs tracking-wider text-center">DIS Chain - The Blockchain Innovation from Meme
                    to AI Integration, Realizing True WEB3</h1>
                <div class="grid grid-cols-1 lg:grid-cols-3 gap-4 mt-12 text-white">
                    <div class="chain-item bg-[#1e2025] px-2 py-4">
                        <img class="w-4" src="../assets/images/icon/eth.png" />
                        <div class="p-1">
                            <h3 class="text-[0.6rem] font-cs py-2">Blockchain Revolution</h3>
                            <p class="text-[0.45rem] font-cr leading-[1.5] tracking-wider">In the world of cryptocurrency,
                                the rise of the PoS (Proof of Stake) mechanism has sparked widespread discussion. Despite
                                the significant improvements in efficiency and energy consumption brought by PoS, this
                                change essentially goes against the original spirit of blockchain decentralization. The PoS
                                mechanism is perceived as leaning towards centralization because it gives individuals or
                                institutions with more tokens greater decision-making power and network control.</p>
                        </div>
                    </div>
                    <div class="chain-item bg-[#1e2025] px-2 py-4">
                        <img class="w-4" src="../assets/images/icon/code.png" />
                        <div class="p-1">
                            <h3 class="text-[0.6rem] font-cs py-2">Technical Innovation</h3>
                            <p class="text-[0.45rem] font-cr leading-[1.5] tracking-wider">DIS Chain supports the Ethereum
                                Virtual Machine (EVM) and is compatible with all Ethereum-based applications and smart
                                contracts, allowing developers to develop and deploy various applications in a familiar and
                                stable environment that supports the Solidity language.</p>
                        </div>
                    </div>
                    <div class="chain-item bg-[#1e2025] px-2 py-4">
                        <img class="w-4" src="../assets/images/icon/bitcoin.png" />
                        <div class="p-1">
                            <h3 class="text-[0.6rem] font-cs py-2">Economic Model</h3>
                            <p class="text-[0.45rem] font-cr leading-[1.5] tracking-wider">Innovative Token Economy System:
                                DIS Chain introduces an innovative token economy system by combining AI computational power
                                with traditional PoW (Proof of Work) mining. In this system, we have introduced the concept
                                of staking mining, creating an unprecedented "Dual Mining Model".</p>
                        </div>
                    </div>
                </div>
            </div>
            <img class="absolute right-0 w-[20rem] top-0" src="../assets/images/bg-02.png" />
        </div>

        <div class="section04 px-4 lg:px-10 py-20 text-center flex flex-col lg:flex-row items-center">
            <div class="flex-1">
                <h1 class="text-base font-cs tracking-wider">Community</h1>
                <p class="text-xs font-cm py-3 text-[#6f7174] w-">Collaborations with social platforms like
                    Linkenetwork, DeNet, promoting DIS Chain on social media.</p>
                <div class="social-box grid grid-cols-3 w-[16rem] mx-auto py-4 divide-x divide-[#d7d7d7] mt-4">
                    <div class="social-item">
                        <img class="w-5 mx-auto" src="../assets/images/icon/discord.png" />
                        <p class="mt-1">Discord</p>
                    </div>
                    <div class="social-item">
                        <img class="w-5 mx-auto" src="../assets/images/icon/telegram.png" />
                        <p class="mt-1">Telegram</p>
                    </div>
                    <div class="social-item">
                        <img class="w-5 mx-auto" src="../assets/images/icon/github.png" />
                        <p class="mt-1">Github</p>
                    </div>
                </div>
            </div>
            <img class="w-[16rem] mt-12 lg:mt-0" src="../assets/images/community-img.png" />
        </div>
        <footer class="footer px-4 lg:px-40 py-8">
            <p class="text-md font-cr text-center">All Rights Reserved @dis | <a href="https://whitepaper.dischain.xyz"
                    target="_blank" class="ml-2 font-cm underline">white paper</a></p>
        </footer>
    </div>
</template>

<script setup>

</script>

<style lang="less" scoped>
.homepage-container {
    // padding-top: 1.4rem;
    min-height: 100vh;
    box-sizing: border-box;
    position: relative;

    .bg-image {
        width: 500px;
        position: absolute;
        left: 0;
        top: 50%;
        opacity: 0.4;
    }

    .section01 {
        height: 100vh;
        background-color: #1559ed;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        position: relative;
        // color: black;
    }

    .section02 {
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
    }

    .section03 {
        background: #000;
        color: white;

        .chain-item {
            border: 1px solid #FFA300;
            border-radius: 0.4rem;
        }
    }

    .section04 {
        .social-box {
            font-size: 15px;
            color: #6f7174;
            font-size: bold;
            border: 1px solid #d7d7d7;
            border-radius: 16px;

            .social-item {
                cursor: pointer;

                &:hover {
                    opacity: 0.8;
                }
            }
        }
    }

    .section05 {
        background: black;
    }

    .footer {
        color: white;
        border-top: 1px solid rgba(255, 255, 255, 0.2);
        background: url('../assets/images/footer-l.png') no-repeat right center / 500px black;
    }
}</style>