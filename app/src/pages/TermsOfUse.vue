<template>
	<v-ons-page>
  		<custom-toolbar v-bind="toolbarInfo"></custom-toolbar>
		<v-ons-card>
			<div id="terms" class="enable_text_select">
			  <p>
			    This is a binding Agreement between NavCoin Developers (“NavCoin” or “We”) and the person, persons, or entity (“You” or “Your”) using the service, Software, or application (“Software”).
			  </p>
			  <p class="terms__heading">
			    RIGHTS AND OBLIGATIONS
			  </p>
			  <p>
			    NavCoin provides the Software solely on the terms and conditions set forth in this Agreement and on the condition that You accept and comply with them. By using the Software You (a) accept this Agreement and agree that You are legally bound by its terms; and (b) represent and warrant that: (i) You are of legal age to enter into a binding agreement; and (ii) if You are a corporation, governmental organization or other legal entity, You have the right, power and authority to enter into this Agreement on behalf of the corporation, governmental organization or other legal entity and bind them to these terms.
			  </p>
			  <p>
			    This Software functions as a free, open source, and multi-signature digital wallet. The Software does not constitute an account where We or other third parties serve as financial intermediaries or custodians of Your NavCoin(s).
			  </p>
			  <p>
			    While the Software has undergone beta testing and continues to be improved by feedback from the open-source user and developer community, We cannot guarantee there will not be bugs in the Software. You acknowledge that Your use of this Software is at Your own discretion and in compliance with all applicable laws. You are responsible for safekeeping Your passwords, private key pairs, PINs, and any other codes You use to access the Software.
			  </p>
			  <p>
			    IF YOU LOSE ACCESS TO YOUR NAV COIN WALLET OR YOUR ENCRYPTED PRIVATE KEYS AND YOU HAVE NOT SEPARATELY STORED A BACKUP OF YOUR WALLET AND CORRESPONDING PASSWORD, YOU ACKNOWLEDGE AND AGREE THAT ANY NAV COIN YOU HAVE ASSOCIATED WITH THAT WALLET WILL BECOME INACCESSIBLE. All transaction requests are irreversible. The authors of the Software, employees and affiliates of NAV COIN, copyright holders, and NAV COIN cannot retrieve Your private keys or passwords if You lose or forget them and cannot guarantee transaction confirmation as they do not have control over the NavCoin network.
			  </p>
			  <p class="terms__heading">
			    DISCLAIMER
			  </p>
			  <p>
			    THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OF THE SOFTWARE, EMPLOYEES AND AFFILIATES OF NAV COIN, COPYRIGHT HOLDERS, OR NAV COIN BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
			  </p>
			  <p>
			    IN NO EVENT WILL NAV COIN OR ITS AFFILIATES, OR ANY OF ITS OR THEIR RESPECTIVE SERVICE PROVIDERS, BE LIABLE TO YOU OR ANY THIRD PARTY FOR ANY USE, INTERRUPTION, DELAY OR INABILITY TO USE THE SOFTWARE, LOST REVENUES OR PROFITS, DELAYS, INTERRUPTION OR LOSS OF SERVICES, BUSINESS OR GOODWILL, LOSS OR CORRUPTION OF DATA, LOSS RESULTING FROM SYSTEM OR SYSTEM SERVICE FAILURE, MALFUNCTION OR SHUTDOWN, FAILURE TO ACCURATELY TRANSFER, READ OR TRANSMIT INFORMATION, FAILURE TO UPDATE OR PROVIDE CORRECT INFORMATION, SYSTEM INCOMPATIBILITY OR PROVISION OF INCORRECT COMPATIBILITY INFORMATION OR BREACHES IN SYSTEM SECURITY, OR FOR ANY CONSEQUENTIAL, INCIDENTAL, INDIRECT, EXEMPLARY, SPECIAL OR PUNITIVE DAMAGES, WHETHER ARISING OUT OF OR IN CONNECTION WITH THIS AGREEMENT, BREACH OF CONTRACT, TORT (INCLUDING NEGLIGENCE) OR OTHERWISE, REGARDLESS OF WHETHER SUCH DAMAGES WERE FORESEEABLE AND WHETHER OR NOT WE WERE ADVISED OF THE POSSIBILITY OF SUCH DAMAGES.
			  </p>
			  <p class="terms__heading">
			    INTELLECTUAL PROPERTY
			  </p>
			  <p>
			    We retain all right, title, and interest in and to the Content and all of NavCoin’s brands, logos, and trademarks, including, but not limited to, NavCoin, NEXT, NEXT Wallet, NEXT Mobile Wallet, and variations of the wording of the aforementioned brands, logos, and trademarks.
			  </p>
			  <p class="terms__heading">
			    CHOICE OF LAW
			  </p>
			  <p>
			    This Agreement, and its application and interpretation, shall be governed exclusively by the laws of the State of Georgia, without regard to its conflict of law rules. You consent to the exclusive jurisdiction of the federal and state courts located in or near Atlanta, Georgia for any dispute arising under this Agreement.
			  </p>
			  <p class="terms__heading">
			    SEVERABILITY
			  </p>
			  <p>
			    In the event any court shall declare any section or sections of this Agreement invalid or void, such declaration shall not invalidate the entire Agreement and all other paragraphs of the Agreement shall remain in full force and effect.
			  </p>
			  <p class="terms__heading">
			    BINDING AGREEMENT
			  </p>
			  <p>
			    The terms and provisions of this Agreement are binding upon Your heirs, successors, assigns, and other representatives. This Agreement may be executed in counterparts, each of which shall be considered to be an original, but both of which constitute the same Agreement.
			  </p>
			  <p>
			    You assume any and all risks associated with the use of the Software. We reserve the right to modify this Agreement from time to time.
			  </p>
			</div>
		</v-ons-card>
	</v-ons-page>
</template>
<script>
export default {
  data() {
    return {
    };
  },
};
</script>
<style>
.terms__heading
{
	font-size:12pt;
	font-weight:bold;
	color:#7D5AB5;
}
</style>