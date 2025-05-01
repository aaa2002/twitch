<template>
  <v-app>
    <v-main
      class="d-flex flex-column align-center justify-center"
      style="height: 100vh"
    >
      <v-container
        class="fill-height d-flex flex-column align-center justify-center text-center"
        style="max-width: 500px"
      >
        <!-- Card 1: Send the song -->
        <v-card elevation="10" class="pa-6 mb-6" rounded="xl">
          <v-card-title class="text-h4 font-weight-bold mb-4">
            Ascultăm și Judecăm
          </v-card-title>
          <v-card-text class="mb-4">
            <span
              >Trimite piesa ta pe mail și ascultă feedback-ul nostru pe
              live!</span
            >
          </v-card-text>

          <v-btn
            :href="mailtoLink"
            color="primary"
            style="text-transform: none"
          >
            Trimite piesa pe mail
          </v-btn>
        </v-card>

        <!-- Card 2: Socials -->
        <v-card elevation="10" class="pa-6" rounded="xl">
          <v-card-title class="text-h5 font-weight-bold mb-4">
            Urmărește-ne
          </v-card-title>
          <v-card-text class="mb-4">
            <span
              >Hai pe Discord sau Twitch pentru a fi la curent cu tot ce facem.
            </span>
          </v-card-text>

          <div class="d-flex justify-center flex-wrap">
            <!-- Discord -->
            <v-btn
              href="https://discord.gg/zKGxdH8jk4"
              target="_blank"
              style="
                background-color: #5865f2;
                text-transform: none;
                color: white;
              "
              class="mb-2 mr-3"
            >
              <svg
                width="24"
                height="24"
                viewBox="0 0 24 24"
                xmlns="http://www.w3.org/2000/svg"
                xmlns:xlink="http://www.w3.org/1999/xlink"
                class="mr-2"
              >
                <rect
                  width="24"
                  height="24"
                  stroke="none"
                  fill="#FFFFFF"
                  opacity="0"
                />

                <g transform="matrix(0.91 0 0 0.91 12 12)">
                  <path
                    style="
                      stroke: none;
                      stroke-width: 1;
                      stroke-dasharray: none;
                      stroke-linecap: butt;
                      stroke-dashoffset: 0;
                      stroke-linejoin: miter;
                      stroke-miterlimit: 4;
                      fill: #ffffff;
                      fill-rule: nonzero;
                      opacity: 1;
                    "
                    transform=" translate(-12, -12)"
                    d="M 19.952 5.672 C 18.048000000000002 4.141 15.036000000000001 3.8819999999999997 14.908000000000001 3.8709999999999996 C 14.707 3.8539999999999996 14.516000000000002 3.9679999999999995 14.434000000000001 4.151999999999999 C 14.428 4.163999999999999 14.362000000000002 4.3149999999999995 14.289000000000001 4.549999999999999 C 15.548000000000002 4.761999999999999 17.095000000000002 5.189999999999999 18.495 6.058999999999999 C 18.719 6.1979999999999995 18.788 6.492999999999999 18.649 6.717999999999999 C 18.559 6.863999999999999 18.402 6.943999999999999 18.242 6.943999999999999 C 18.156000000000002 6.943999999999999 18.069000000000003 6.920999999999999 17.990000000000002 6.871999999999999 C 15.584 5.38 12.578 5.305 12 5.305 C 11.422 5.305 8.415 5.38 6.011 6.872 C 5.7860000000000005 7.012 5.492 6.942 5.352 6.718 C 5.212000000000001 6.493 5.282 6.199 5.506 6.059 C 6.906000000000001 5.191 8.452 4.7620000000000005 9.712 4.550000000000001 C 9.638 4.314000000000001 9.572 4.164000000000001 9.567 4.152000000000001 C 9.484 3.968 9.294 3.852 9.092 3.872 C 8.965 3.8819999999999997 5.953000000000001 4.141 4.023000000000001 5.694 C 3.015 6.625 1 12.073 1 16.783 C 1 16.866 1.022 16.948 1.063 17.02 C 2.4539999999999997 19.463 6.247999999999999 20.103 7.1129999999999995 20.131 C 7.117999999999999 20.131 7.122999999999999 20.131 7.127999999999999 20.131 C 7.280999999999999 20.131 7.424999999999999 20.058 7.514999999999999 19.934 L 8.389999999999999 18.732 C 6.030999999999999 18.122 4.825999999999999 17.087 4.7559999999999985 17.026 C 4.557999999999998 16.851 4.538999999999999 16.549 4.713999999999999 16.351 C 4.8889999999999985 16.153 5.189999999999999 16.134 5.387999999999999 16.308 C 5.416999999999999 16.334 7.635999999999999 18.217 12 18.217 C 16.372 18.217 18.591 16.326 18.613 16.307 C 18.811 16.134999999999998 19.113 16.153 19.287 16.352 C 19.461 16.55 19.442 16.851 19.244999999999997 17.025 C 19.174999999999997 17.087 17.97 18.121 15.610999999999997 18.730999999999998 L 16.485999999999997 19.933 C 16.575999999999997 20.057 16.72 20.13 16.872999999999998 20.13 C 16.877999999999997 20.13 16.883 20.13 16.887999999999998 20.13 C 17.752999999999997 20.102999999999998 21.546999999999997 19.462999999999997 22.938 17.019 C 22.978 16.947 23 16.866 23 16.783 C 23 12.073 20.985 6.625 19.952 5.672 z M 8.891 14.87 C 7.967 14.87 7.2170000000000005 14.013 7.2170000000000005 12.956999999999999 C 7.2170000000000005 11.900999999999998 7.966 11.043999999999999 8.891 11.043999999999999 C 9.815999999999999 11.043999999999999 10.565 11.900999999999998 10.565 12.956999999999999 C 10.565 14.013 9.816 14.87 8.891 14.87 z M 15.109 14.87 C 14.185 14.87 13.435 14.013 13.435 12.956999999999999 C 13.435 11.900999999999998 14.184000000000001 11.043999999999999 15.109 11.043999999999999 C 16.033 11.043999999999999 16.783 11.900999999999998 16.783 12.956999999999999 C 16.783 14.013 16.033 14.87 15.109 14.87 z"
                    stroke-linecap="round"
                  />
                </g>
              </svg>
              Discord
            </v-btn>

            <!-- Twitch -->
            <v-btn
              href="https://www.twitch.tv/iustin_hvnds"
              target="_blank"
              style="
                background-color: #9146ff;
                text-transform: none;
                color: white;
              "
              class="mb-2"
            >
              <svg
                id="Twitch_24"
                width="24"
                height="24"
                viewBox="0 0 24 24"
                xmlns="http://www.w3.org/2000/svg"
                xmlns:xlink="http://www.w3.org/1999/xlink"
                class="mr-2"
              >
                <rect
                  width="24"
                  height="24"
                  stroke="none"
                  fill="#FFFFFF"
                  opacity="0"
                />

                <g transform="matrix(0.95 0 0 0.95 12 12)">
                  <path
                    style="
                      stroke: none;
                      stroke-width: 1;
                      stroke-dasharray: none;
                      stroke-linecap: butt;
                      stroke-dashoffset: 0;
                      stroke-linejoin: miter;
                      stroke-miterlimit: 4;
                      fill: #ffffff;
                      fill-rule: nonzero;
                      opacity: 1;
                    "
                    transform=" translate(-12, -12.5)"
                    d="M 5.3632812 2 L 2 6.6367188 L 2 20 L 7 20 L 7 23 L 10 23 L 13 20 L 17 20 L 22 15 L 22 2 L 5.3632812 2 z M 6 4 L 20 4 L 20 13 L 17 16 L 12 16 L 9 19 L 9 16 L 6 16 L 6 4 z M 11 7 L 11 12 L 13 12 L 13 7 L 11 7 z M 16 7 L 16 12 L 18 12 L 18 7 L 16 7 z"
                    stroke-linecap="round"
                  />
                </g>
              </svg>
              Twitch
            </v-btn>
          </div>
        </v-card>
      </v-container>
    </v-main>
  </v-app>
</template>

<script setup>
const subject = "Ascultam si Judecam";
const body = "Salut! Iata piesa mea pentru Ascultam si Judecam.";
const mailtoLink = `mailto:ascultamsijudecam@outlook.com?subject=${encodeURIComponent(
  subject
)}&body=${encodeURIComponent(body)}`;
</script>
