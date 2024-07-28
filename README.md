# kchra
"use client";
/** @jsxImportSource @emotion/react */
import styled from "@emotion/styled";
import React from "react";

const Main = styled.div`
  display: inline-flex;
  align-items: flex-start;
  gap: 20px;
  width: 1366px;
  flex-shrink: 0;
  align-self: stretch;
  background: var(--Zeb_Solid-BG_Blue, #222245);

  /* Shadows/7dp */
  box-shadow: 0px 7px 7px -2px rgba(97, 79, 79, 0.14);
`;
const BlogsShimmer = styled.div`
  display: flex;
  width: 85.375rem;
  height: 50rem;
  justify-content: center;
  align-items: center;
`;
const PageLevel = styled.div`
  width: 85.375rem;
  flex-shrink: 0;
  align-self: stretch;
  background: var(--Zeb_Solid-BG_Blue, #222245);

  /* Shadows/7dp */
  box-shadow: 0px 7px 7px -2px rgba(97, 79, 79, 0.14);
`;
const Frame48096510 = styled.div`
  display: inline-flex;
  align-items: center;
  gap: 1.25rem;
`;

const Graph = styled.div`
  display: flex;
  flex-direction: column;
  width: 47.5rem;
  height: 39.75rem;
  padding: 1rem;
  justify-content: center;
  align-items: flex-start;
  gap: 1.25rem;
  border-radius: 0.5rem;
  background: var(--blue-02-dark-blue, #181837);
`;
const Frame48096487 = styled.div`
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  gap: 1.25rem;
  flex: 1 0 0;
  align-self: stretch;
`;
const PredictionCards = styled.div`
  display: flex;
  padding: 1rem;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  gap: 1.25rem;
  align-self: stretch;
  border-radius: 0.5rem;
  background: var(--Zeb_Solid-BG_Blue, #222245);
`;
const Rightsidecards = styled.div`
  display: flex;
  width: 19.5rem;
  height: 39.75rem;
  flex-direction: column;
  align-items: flex-start;
  gap: 1rem;
`;

const Breakdown = styled.div`
  display: flex;
  padding: 1rem;
  flex-direction: column;
  justify-content: space-between;
  align-items: flex-start;
  flex: 1 0 0;
  align-self: stretch;
  border-radius: 0.5rem;
  background: var(--blue-02-dark-blue, #181837);
`;

const Component15 = styled.div`
  display: flex;
  height: 17.125rem;
  flex-direction: column;
  align-items: center;
  gap: 0.75rem;
  align-self: stretch;
  border-radius: 0.5rem;
  background: var(
    --Shimmer-DarkBlue_Shimmer,
    linear-gradient(97deg, #34345a -40.76%, #19193a 135.88%)
  );
`;
const CurrentValue = styled.div`
  display: flex;
  padding: 1rem;
  flex-direction: column;
  align-items: flex-start;
  gap: 1.25rem;
  align-self: stretch;
  border-radius: 0.5rem;
  background: var(
    --Zeb_Gradient-Dark_Blue,
    linear-gradient(254deg, #4a62ca -43.42%, #1b264b 148.58%)
  );
`;
const Headercontent = styled.div`
  width: 3.375rem;
  height: 3.375rem;
  fill: var(
    --Shimmer-Gradient_Shimmer,
    linear-gradient(
      90deg,
      rgba(233, 239, 246, 0.1) 0%,
      rgba(207, 207, 207, 0.02) 99.74%
    )
  );
`;

const Frame461 = styled.div`
  display: flex;
width: 11.875rem;
height: 1.5rem;
align-items: center;
gap: 0.25rem;
border-radius: 0.25rem;
background: var(--Shimmer-DarkBlue_Shimmer, linear-gradient(97deg, #34345A -40.76%, #19193A 135.88%));
`;
const Field = styled.div`
  display: flex;
height: 4.25rem;
flex-direction: column;
align-items: flex-start;
gap: 0.25rem;
flex: 1 0 0;
`;
const Frame461a = styled.div`
display: flex;
width: 3.125rem;
height: 1.125rem;
align-items: center;
gap: 0.25rem;
border-radius: 0.25rem;
background: var(--Shimmer-BGBlue_Shimmer, linear-gradient(97deg, rgba(61, 61, 102, 0.92) -40.76%, #1E1E41 135.88%));
`;
const Frame461l = styled.div`
display: flex;
height: 2.5rem;
padding: 0.5rem 0.75rem;
align-items: center;
gap: 0.75rem;
flex-shrink: 0;
align-self: stretch;
border-radius: 0.5rem;
background: var(--Shimmer-BGBlue_Shimmer, linear-gradient(97deg, rgba(61, 61, 102, 0.92) -40.76%, #1E1E41 135.88%));
`;
const Frame461b = styled.div`
display: flex;
width: 8.125rem;
height: 1.125rem;
align-items: center;
gap: 0.25rem;
border-radius: 0.25rem;
background: var(--Shimmer-BGBlue_Shimmer, linear-gradient(97deg, rgba(61, 61, 102, 0.92) -40.76%, #1E1E41 135.88%));

`;
const Frame461c = styled.div`
display: flex;
width: 4.375rem;
height: 1.125rem;
align-items: center;
gap: 0.25rem;
border-radius: 0.25rem;
background: var(--Shimmer-BGBlue_Shimmer, linear-gradient(97deg, rgba(61, 61, 102, 0.92) -40.76%, #1E1E41 135.88%));
`;
const Frame365 = styled.div`
display: flex;
height: 2.5rem;
padding: 0.5rem 0.75rem;
align-items: center;
gap: 0.75rem;
flex-shrink: 0;
align-self: stretch;
border-radius: 0.5rem;
background: var(--Shimmer-BGBlue_Shimmer, linear-gradient(97deg, rgba(61, 61, 102, 0.92) -40.76%, #1E1E41 135.88%));
`;

const Component15a = styled.div`
  display: flex;
height: 18.875rem;
flex-direction: column;
align-items: center;
gap: 0.75rem;
align-self: stretch;
border-radius: 0.5rem;
background: var(--Shimmer-DarkBlue_Shimmer, linear-gradient(97deg, #34345A -40.76%, #19193A 135.88%));
`;
const Front = styled.div`
 
  display: flex;
align-items: flex-start;
gap: 1.25rem;
align-self: stretch;
`;
const Component15b = styled.div`
display: flex;
height: 8.875rem;
flex-direction: column;
align-items: center;
gap: 0.75rem;
align-self: stretch;
border-radius: 0.5rem;
background: var(--Shimmer-DarkBlue_Shimmer, linear-gradient(97deg, #34345A -40.76%, #19193A 135.88%));
`;
const Buttonn = styled.div`
display: flex;
width: 43.5625rem;
height: 2.125rem;
padding: 0.5rem 0.75rem;
flex-direction: column;
justify-content: center;
align-items: flex-end;
gap: 0.5rem;
border-radius: 0.5rem;
background: var(--Shimmer-BGBlue_Shimmer, linear-gradient(97deg, rgba(61, 61, 102, 0.92) -40.76%, #1E1E41 135.88%));
`;
const Headercontent1 = styled.div`
display: flex;
height: 1.25rem;
justify-content: center;
align-items: center;
gap: 0.25rem;
align-self: stretch;
border-radius: 0.25rem;
background: var(--Shimmer-Gradient_Shimmer, linear-gradient(90deg, rgba(233, 239, 246, 0.10) 0%, rgba(207, 207, 207, 0.02) 99.74%));
`;
const Roww = styled.div`
display: flex;
align-items: flex-start;

`;
const Coll = styled.div`
display: flex;

`;

const LoadingState = () => {
  return (
    <Main>
      <Frame48096510>
        <Graph>
          <Frame48096487>
            <PredictionCards>
              <Frame461></Frame461>
              <Frame461a></Frame461a>
              <Frame365></Frame365>
              <Front>
              <Field>
              <Frame461b></Frame461b>
              <Frame461l></Frame461l>
              </Field>
              <Field>
              <Frame461c></Frame461c>
              <Frame461l></Frame461l>
              </Field>
              </Front>
              <Buttonn></Buttonn>
            </PredictionCards>
            <Component15></Component15>
          </Frame48096487>
        </Graph>
        <Rightsidecards>
          <Breakdown>
            <CurrentValue>
              <Roww>
              <Headercontent>
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="54"
                  height="54"
                  viewBox="0 0 54 54"
                  fill="none"
                >
                  <rect
                    width="54"
                    height="54"
                    rx="4"
                    fill="url(#paint0_linear_2440_501784)"
                  />
                  <defs>
                    <linearGradient
                      id="paint0_linear_2440_501784"
                      x1="0"
                      y1="0"
                      x2="54.2083"
                      y2="0.352339"
                      gradientUnits="userSpaceOnUse"
                    >
                      <stop stop-color="#E9EFF6" stop-opacity="0.1" />
                      <stop
                        offset="1"
                        stop-color="#CFCFCF"
                        stop-opacity="0.02"
                      />
                    </linearGradient>
                  </defs>
                </svg>
              </Headercontent>
              <Coll>
              <Headercontent1></Headercontent1>
              <Headercontent1></Headercontent1>
              </Coll>
              </Roww>
              
            </CurrentValue>
            <Frame461></Frame461>
            <Component15a></Component15a>
            <Component15b></Component15b>
          </Breakdown>
        </Rightsidecards>
      </Frame48096510>
    </Main>
  );
};

export default LoadingState;
