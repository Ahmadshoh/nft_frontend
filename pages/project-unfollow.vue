<template>
  <div class="main-page">

    <div class="page-top bottom">
      <div class="wrapper">
        <div class="breadcrumbs">
          <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Active</a></li>
            <li>EtherBear #215</li>
          </ul>
        </div>
      </div>
    </div>

    <div class="project">
      <div class="wrapper wrapper_big">
        <div class="project__body flex">
          <div class="project__left">
            <div class="bottom">
              <div class="project__title">EtherBear</div>
              <div class="project__left-top flex">
                <div class="active-item">Active</div>
                <div class="star star_good flex">
                  <img src="@/assets/img/catalog/star.svg" alt="">
                  <span>8.0</span>
                </div>
                <div class="category category_amber">collectible</div>
              </div>
            </div>
            <div class="project__profile flex bottom">
              <div class="project__avatar img-cover">
                <img src="@/assets/img/project/avatar.jpg" alt="">
              </div>
              <div class="project__profile-box">
                <div class="project__profile-caption">Start date</div>
                <div class="project__profile-date">05-04-2021 3:00PM UTC</div>
              </div>
            </div>
            <div class="timer bottom">
              <div class="timer__caption">before the start</div>
              <div class="countdown">
                <div class="timer__section">
                  <span class="count" id="days"></span>
                </div>
                <div class="timer__section">
                  <span class="count" id="hours"></span>
                </div>
                <div class="timer__section">
                  <span class="count" id="minutes"></span>
                </div>
                <div class="timer__section">
                  <span class="count" id="seconds"></span>
                </div>
              </div>
            </div>
            <div class="project__buttons flex bottom">
              <a href="#" class="project__btn btn btn_blue">
                <div class="btn__caption">site project</div>
                <div class="btn__icon svg-contain">
                  <svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path fill-rule="evenodd" clip-rule="evenodd"
                          d="M9.33334 1.99967C9.33334 1.63148 9.63182 1.33301 10 1.33301H14C14.3682 1.33301 14.6667 1.63148 14.6667 1.99967C14.6667 2.36786 14.3682 2.66634 14 2.66634H10C9.63182 2.66634 9.33334 2.36786 9.33334 1.99967Z" fill="white" />
                    <path fill-rule="evenodd" clip-rule="evenodd"
                          d="M14 1.33301C14.3682 1.33301 14.6667 1.63148 14.6667 1.99967V5.99967C14.6667 6.36786 14.3682 6.66634 14 6.66634C13.6318 6.66634 13.3333 6.36786 13.3333 5.99967V1.99967C13.3333 1.63148 13.6318 1.33301 14 1.33301Z"
                          fill="white" />
                    <path fill-rule="evenodd" clip-rule="evenodd"
                          d="M13.8047 2.19526C14.0651 2.45561 14.0651 2.87772 13.8047 3.13807L9.13807 7.80474C8.87772 8.06509 8.45561 8.06509 8.19526 7.80474C7.93491 7.54439 7.93491 7.12228 8.19526 6.86193L12.8619 2.19526C13.1223 1.93491 13.5444 1.93491 13.8047 2.19526Z"
                          fill="white" />
                    <path fill-rule="evenodd" clip-rule="evenodd"
                          d="M2.66667 3.33268C2.66667 2.96449 2.96515 2.66602 3.33334 2.66602H7.33334C7.70153 2.66602 8 2.96449 8 3.33268C8 3.70087 7.70153 3.99935 7.33334 3.99935H4.00001V11.9993H12V8.66602C12 8.29783 12.2985 7.99935 12.6667 7.99935C13.0349 7.99935 13.3333 8.29783 13.3333 8.66602V12.666C13.3333 13.0342 13.0349 13.3327 12.6667 13.3327H3.33334C2.96515 13.3327 2.66667 13.0342 2.66667 12.666V3.33268Z"
                          fill="white" />
                  </svg>
                </div>
              </a>
              <a href="#" class="project__btn btn unfollow">
                <div class="btn__icon svg-contain">
                  <svg width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
                    <path
                      d="M11.1564 6.05293C11.2263 5.9878 11.2826 5.90954 11.3222 5.82263C11.3619 5.73571 11.384 5.64185 11.3873 5.54639C11.3907 5.45093 11.3752 5.35575 11.3417 5.26628C11.3083 5.1768 11.2576 5.0948 11.1924 5.02493C11.1273 4.95507 11.049 4.89872 10.9621 4.8591C10.8752 4.81948 10.7813 4.79737 10.6859 4.79403C10.5904 4.79068 10.4952 4.80618 10.4058 4.83962C10.3163 4.87306 10.2343 4.9238 10.1644 4.98893L8.03642 6.97293L6.05241 4.8442C5.91966 4.70824 5.73897 4.62963 5.54899 4.6252C5.35902 4.62077 5.17485 4.69087 5.03591 4.8205C4.89696 4.95013 4.81427 5.129 4.80553 5.31882C4.79679 5.50865 4.8627 5.69435 4.98914 5.8362L6.97314 7.9642L4.84441 9.9482C4.77208 10.0127 4.71337 10.091 4.67171 10.1784C4.63005 10.2659 4.6063 10.3609 4.60184 10.4576C4.59739 10.5544 4.61232 10.6511 4.64576 10.7421C4.6792 10.833 4.73047 10.9164 4.79657 10.9872C4.86267 11.0581 4.94226 11.115 5.03067 11.1547C5.11908 11.1943 5.21452 11.2159 5.31139 11.2182C5.40826 11.2204 5.50461 11.2033 5.59477 11.1678C5.68493 11.1323 5.76708 11.0792 5.83641 11.0115L7.96442 9.0282L9.94842 11.1562C10.0125 11.2299 10.0907 11.2899 10.1785 11.3327C10.2662 11.3755 10.3617 11.4001 10.4592 11.4052C10.5567 11.4104 10.6542 11.3958 10.7459 11.3624C10.8377 11.329 10.9217 11.2775 10.9931 11.2109C11.0645 11.1444 11.1218 11.0641 11.1615 10.9749C11.2013 10.8857 11.2226 10.7895 11.2244 10.6919C11.2261 10.5943 11.2082 10.4973 11.1716 10.4068C11.1351 10.3162 11.0807 10.234 11.0117 10.1649L9.02841 8.03693L11.1564 6.05293Z"
                      fill="white" />
                    <path fill-rule="evenodd" clip-rule="evenodd"
                          d="M0 8C0 3.58182 3.58182 0 8 0C12.4182 0 16 3.58182 16 8C16 12.4182 12.4182 16 8 16C3.58182 16 0 12.4182 0 8ZM8 14.5455C7.14044 14.5455 6.28929 14.3762 5.49516 14.0472C4.70103 13.7183 3.97947 13.2361 3.37166 12.6283C2.76386 12.0205 2.28173 11.299 1.95279 10.5048C1.62385 9.71071 1.45455 8.85956 1.45455 8C1.45455 7.14044 1.62385 6.28929 1.95279 5.49516C2.28173 4.70103 2.76386 3.97947 3.37166 3.37166C3.97947 2.76386 4.70103 2.28173 5.49516 1.95279C6.28929 1.62385 7.14044 1.45455 8 1.45455C9.73596 1.45455 11.4008 2.14415 12.6283 3.37166C13.8558 4.59918 14.5455 6.26404 14.5455 8C14.5455 9.73596 13.8558 11.4008 12.6283 12.6283C11.4008 13.8558 9.73596 14.5455 8 14.5455Z"
                          fill="white" />
                  </svg>
                </div>
                <div class="btn__caption">unfollow</div>
              </a>
            </div>
            <div class="social-item bottom">
              <div class="social-item__caption">project links</div>
              <div class="social-item__list flex">
                <div class="social-item__coll">
                  <a href="#" class="social-item__link flex">
                    <div class="social-item__icon img-contain">
                      <img src="@/assets/img/project/social/mail.svg" alt="">
                      <img src="@/assets/img/project/social/mail-hover.svg" alt="">
                    </div>
                    <div class="social-item__name">Email</div>
                  </a>
                  <a href="#" class="social-item__link flex">
                    <div class="social-item__icon img-contain">
                      <img src="@/assets/img/project/social/discord.svg" alt="">
                      <img src="@/assets/img/project/social/discord-hover.svg" alt="">
                    </div>
                    <div class="social-item__name">Discord </div>
                  </a>
                  <a href="#" class="social-item__link flex">
                    <div class="social-item__icon img-contain">
                      <img src="@/assets/img/project/social/medium.svg" alt="">
                      <img src="@/assets/img/project/social/medium-hover.svg" alt="">
                    </div>
                    <div class="social-item__name">Medium</div>
                  </a>
                  <a href="#" class="social-item__link flex">
                    <div class="social-item__icon img-contain">
                      <img src="@/assets/img/project/social/site.svg" alt="">
                      <img src="@/assets/img/project/social/site-hover.svg" alt="">
                    </div>
                    <div class="social-item__name">site.ru</div>
                  </a>
                </div>
                <div class="social-item__coll">
                  <a href="#" class="social-item__link flex">
                    <div class="social-item__icon img-contain">
                      <img src="@/assets/img/project/social/telegram.svg" alt="">
                      <img src="@/assets/img/project/social/telegram-hover.svg" alt="">
                    </div>
                    <div class="social-item__name">Telegram <small>(142k followers)</small></div>
                  </a>
                  <a href="#" class="social-item__link flex">
                    <div class="social-item__icon img-contain">
                      <img src="@/assets/img/project/social/instagram.svg" alt="">
                      <img src="@/assets/img/project/social/instagram-hover.svg" alt="">
                    </div>
                    <div class="social-item__name">Instagram <small>(142k followers)</small></div>
                  </a>
                  <a href="#" class="social-item__link flex">
                    <div class="social-item__icon img-contain">
                      <img src="@/assets/img/project/social/facebook.svg" alt="">
                      <img src="@/assets/img/project/social/facebook-hover.svg" alt="">
                    </div>
                    <div class="social-item__name">Facebook <small>(142k followers)</small></div>
                  </a>
                  <a href="#" class="social-item__link flex">
                    <div class="social-item__icon img-contain">
                      <img src="@/assets/img/project/social/twitter.svg" alt="">
                      <img src="@/assets/img/project/social/twitter-hover.svg" alt="">
                    </div>
                    <div class="social-item__name">Twitter <small>(142k followers)</small></div>
                  </a>
                </div>
              </div>
            </div>
          </div>
          <div class="project__right">
            <div class="project__wrap bottom">
              <div class="arrow arrow_prew">
                <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path fill-rule="evenodd" clip-rule="evenodd"
                        d="M16.875 10.0002C16.875 9.57833 16.533 9.23633 16.1111 9.23633H3.88889C3.467 9.23633 3.125 9.57833 3.125 10.0002C3.125 10.4221 3.467 10.7641 3.88889 10.7641H16.1111C16.533 10.7641 16.875 10.4221 16.875 10.0002Z"
                        fill="#3340B4" />
                  <path fill-rule="evenodd" clip-rule="evenodd"
                        d="M9.77626 4.11241C9.47794 3.81409 8.99428 3.81409 8.69596 4.11241L3.34874 9.45963C3.05042 9.75795 3.05042 10.2416 3.34874 10.5399L8.69596 15.8872C8.99428 16.1855 9.47794 16.1855 9.77626 15.8872C10.0746 15.5888 10.0746 15.1052 9.77626 14.8069L4.96919 9.99978L9.77626 5.19271C10.0746 4.89439 10.0746 4.41073 9.77626 4.11241Z"
                        fill="#3340B4" />
                </svg>
              </div>
              <div class="arrow arrow_next">
                <svg width="20" height="20" viewBox="0 0 20 20" fill="none" xmlns="http://www.w3.org/2000/svg">
                  <path fill-rule="evenodd" clip-rule="evenodd"
                        d="M3.12524 9.99881C3.12524 10.4207 3.46725 10.7627 3.88913 10.7627L16.1114 10.7627C16.5332 10.7627 16.8752 10.4207 16.8752 9.99881C16.8752 9.57693 16.5332 9.23492 16.1114 9.23492L3.88913 9.23492C3.46725 9.23492 3.12524 9.57692 3.12524 9.99881Z"
                        fill="#3340B4" />
                  <path fill-rule="evenodd" clip-rule="evenodd"
                        d="M10.224 15.8866C10.5223 16.1849 11.006 16.1849 11.3043 15.8866L16.6515 10.5394C16.9498 10.2411 16.9498 9.75741 16.6515 9.45909L11.3043 4.11187C11.006 3.81355 10.5223 3.81355 10.224 4.11187C9.92567 4.41018 9.92567 4.89385 10.224 5.19217L15.0311 9.99924L10.224 14.8063C9.92566 15.1046 9.92566 15.5883 10.224 15.8866Z"
                        fill="#3340B4" />
                </svg>
              </div>
              <div class="project__slick">
                <div class="project__slide swiper-slide">
                  <div class="project__slide-box img-cover">
                    <img src="@/assets/img/project/img-1.jpg" alt="">
                  </div>
                </div>
                <div class="project__slide swiper-slide">
                  <div class="project__slide-box img-cover">
                    <img src="@/assets/img/project/img-2.jpg" alt="">
                  </div>
                </div>
                <div class="project__slide swiper-slide">
                  <div class="project__slide-box img-cover">
                    <img src="@/assets/img/project/img-3.jpg" alt="">
                  </div>
                </div>
                <div class="project__slide swiper-slide">
                  <div class="project__slide-box img-cover">
                    <img src="@/assets/img/project/img-2.jpg" alt="">
                  </div>
                </div>
              </div>
            </div>
            <div class="project__items bottom">
              <div class="project__item">
                <div class="project__item-caption">Min price</div>
                <div class="project__item-desc">$0.01</div>
              </div>
              <div class="project__item">
                <div class="project__item-caption">Max price</div>
                <div class="project__item-desc">$239</div>
              </div>
              <div class="project__item">
                <div class="project__item-caption">Available for sale</div>
                <div class="project__item-desc">1 000 000 tokens</div>
              </div>
            </div>
            <div class="project__row flex bottom">
              <div class="project__coll">
                <div class="project__coll-item flex">
                  <div class="project__coll-caption">Website:</div>
                  <a href="#" class="project__coll-link">mariotestino-nft.art</a>
                </div>
                <div class="project__coll-item flex">
                  <div class="project__coll-caption">Calebrity:</div>
                  <a href="#" class="project__coll-link">Mario Testino</a>
                </div>
                <div class="project__coll-item flex">
                  <div class="project__coll-caption">Available on:</div>
                  <a href="#" class="project__coll-link">OpenSea.io</a>
                </div>
              </div>
              <div class="project__coll">
                <div class="project__coll-item flex">
                  <div class="project__coll-caption">BlockChain:</div>
                  <a href="#" class="project__coll-info flex">
                    <div class="project__coll-icon">
                      <img src="@/assets/img/project/icon-1.svg" alt="">
                    </div>
                    <div class="project__coll-name">Ethereum (ETH)</div>
                  </a>
                </div>
                <div class="project__coll-item flex">
                  <div class="project__coll-caption">Platform:</div>
                  <a href="#" class="project__coll-info flex">
                    <div class="project__coll-icon">
                      <img src="@/assets/img/project/icon-2.svg" alt="">
                    </div>
                    <div class="project__coll-name">Dmarket</div>
                  </a>
                </div>
              </div>
            </div>
            <div class="project__article bottom">
              <h2>About</h2>
              <p>The Agoric testnet is a series of global, competitive challenges for validators to prepare, learn, and earn points in advance of Agoric's mainnet. The testnet will consist of five (5) phases, each phase focused on testing a different
                aspect of validating and securing the Agoric blockchain network. Points are earned by completing network and community tasks during each phase, with bonus points awarded to the winners of the challenge tasks. The Agoric testnet is a
                series of global, competitive challenges for validators to prepare, learn, and earn points in advance of Agoric's mainnet. The testnet will consist of five (5) phases, each phase focused on testing a different aspect of validating and
                securing the Agoric blockchain network. </p>
            </div>
            <div class="project__article bottom">
              <h2>Testnet Goals</h2>
              <ol>
                <li>Secure the Network Scale # of validators on our network. Take part in governance and upgrades, and keep the Agoric chain secure.</li>
                <li>Train and Prepare Validators Prepare validators to be ready for mainnet. Learn about the nuances of running a node for mainnet and earn points.</li>
                <li>Grow Community We want to work with the best people from all over the world. A diverse network of validators is the way forward to a strong network.</li>
              </ol>
            </div>
            <div class="project__article bottom">
              <h2>Getting Started</h2>
              <ol>
                <li>Join the <a href="#">Agoric Discord Server</a></li>
                <li>Complete the testnet <a href="#">application form</a> (if you don't have a node yet, more info below)</li>
                <li>If your application is approved, Agoric will send you an email with a link to complete KYC/AML.</li>
                <li>Agoric will then confirm your KYC/AML approval by email.</li>
                <li>Agoric will then give you a unique tag on the Discord giving you access to an incentivized testnet channel.</li>
                <li>You can now (if you haven't) set up your node by following the <a href="#">Validator Setup Guide</a> and add your Public Key into your original application form.</li>
              </ol>
            </div>
          </div>
        </div>
      </div>
    </div>

  </div>
</template>
